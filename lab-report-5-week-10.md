# Finding tests with different results

- To find differences in the terminal output I first made the ouput be copied over to a file called `results.txt` with the `>` command following `bash script.sh`
- I then ran `diff` along with the file location of `results.txt` for both the given repository and my repository which listed the differences among the `results.txt` file.

---

# First Test

- The first test is: `[a](url &quot;tit&quot;)` (Test 41)

- Ouputs (Top is given, bottom is mine)

![image](https://user-images.githubusercontent.com/90485689/157862893-ea38e057-de7d-43f2-a425-48e232ab1332.png)

- I think my implementation is correct since the `&` does not give any issues to the preview on vscode.

- The possible bug with the given repo is that since .trim() does not remove the spaces in between two words, once the code reaches the if statement, the indexOf statement will return a positive value since a space was found.

![image](https://user-images.githubusercontent.com/90485689/157866591-8318d87c-1796-4147-a49c-9733e00c1b8b.png)

---

# Second Test

- The second test is: `[link] bar](/uri)` (Test 512)

- Outputs (Top is given, bottom is mine)

![image](https://user-images.githubusercontent.com/90485689/157868401-54fe5b1c-d9be-4c0b-aaa9-0bb181dae36b.png)


- I think my implementation is correct since the `]` is followed by another `]` meaning that anything after the `()` does not count as a link.

- The issue with the given repo is that it does not check if the main brackets `][)(` are followed by something that would break the structure of a link --> `[]()` such as another close bracket, or a close parenthesis.

![image](https://user-images.githubusercontent.com/90485689/157870295-7e60d3cd-1995-4303-9c41-05cb850f519b.png)

---
