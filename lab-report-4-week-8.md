# **My Implementation Of Markdown Parse**

[My Markdown Repo](https://github.com/HyperBlitzer/markdown-parse)

## Snippet 1

### Test 1

![image](https://user-images.githubusercontent.com/90485689/155660155-384b75a0-9442-4531-9007-589630558ff8.png)

### Test 1 Output

![image](https://user-images.githubusercontent.com/90485689/155660234-00e4f870-8f0a-4b0e-8bb7-0475de406930.png)

### Test 1 Question

- I think that fixing this test will require less than 10 lines of code.
- A possible solution is checking if the character before `[` or inbetween `]` and `(` is a backtick.
- If a backtick exists then you have to find the next backtick and ignore the text inbetween the backticks.

---

## Snippet 2

### Test 2

![image](https://user-images.githubusercontent.com/90485689/155660071-212a4a2a-ea92-44d5-94ba-782cbc680b92.png)

### Test 2 Output

![image](https://user-images.githubusercontent.com/90485689/155660036-a64d1628-0cfd-484b-aa28-7a7f008042a5.png)

### Test 2 Question

- I don't think that fixing the issue with nested brackets and parenthesis is possible with less than 10 lines of code.
- I am not sure how to actually fix this issue since I first thought of checking where a closing bracket was followed by a parenthesis, but the snippet also includes that combo of characters nested in two brackets.

---

## Snippet 3

### Test 3

![image](https://user-images.githubusercontent.com/90485689/155659588-e0640fea-eeb0-4f3c-a8cb-68a13a2b86bc.png)

### Test 3 Output

![image](https://user-images.githubusercontent.com/90485689/155659649-137db39e-0ee0-48fe-87e7-ce91a529e57e.png)

### Test 3 Question

- There was no Junit output meaning that an infinte loop occured.
- To fix this test I think that the possible solution is using trim, less than 10 lines, to remove the spaces that separate the different lines.

---

# **Implementation I reviewed**

[Reviewed Markdown Repo](https://github.com/iireneliao/markdown-parse)

## Snippet 1

### Test 1

![image](https://user-images.githubusercontent.com/90485689/155660860-abe82941-ad48-48fe-9c8f-b8cb4d692360.png)

### Test 1 Output

![image](https://user-images.githubusercontent.com/90485689/155660811-bdced176-d2d5-486f-972e-4d2799407b86.png)

---

## Snippet 2

### Test 2

![image](https://user-images.githubusercontent.com/90485689/155660943-ab387637-6c97-4fa8-a7ec-4429576c8445.png)

### Test 2 Output

![image](https://user-images.githubusercontent.com/90485689/155661013-1fe4b72a-f780-4ecf-a30a-c5303e78225c.png)

---

## Snippet 3

### Test 3

![image](https://user-images.githubusercontent.com/90485689/155661202-7411c81e-1e47-42e7-9e1e-c901151fcaac.png)

### Test 3 Output

![image](https://user-images.githubusercontent.com/90485689/155661161-690cf41d-24ac-4295-ba12-6644f6eb886c.png)

---
