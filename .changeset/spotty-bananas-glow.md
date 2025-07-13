---
"@wdio/ocr-service": minor
---

\- Inside browser command, the OCR functions are called directly with secured context instead of calling the browser function itself (to avoir loop from issue 657)

\- Inside browser command, the OCR functions are first add to the Multi Remote browser with a loop and another version in Single Remote still is added to each instances (similar than  the issue 983)