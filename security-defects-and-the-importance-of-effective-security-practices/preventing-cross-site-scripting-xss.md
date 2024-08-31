# Preventing cross-site scripting (XSS)

#### 1. **Output Encoding**

* **HTML Encoding**: Convert special HTML characters (like `<`, `>`) into HTML entities (`&lt;`, `&gt;`) to prevent them from being interpreted as HTML or JavaScript by the browser.
* **URL Encoding**: Use URL encoding for special characters in URLs to prevent XSS in URL parameters.
* **Special Cases**: Be cautious of corner cases like UTF-7 encoding; ensure the browser renders pages in UTF-8 to avoid issues.

#### 2. **JavaScript-Specific Considerations**

* **Escape Characters in JavaScript**: When rendering user data as part of JavaScript, escape special characters like single quotes (`'`) to prevent code injection.
* **Avoid `innerHTML`**: Using `innerHTML` can lead to XSS if user input is directly inserted. Instead, use `textContent` or `innerText` to insert text safely.
* **Avoid `eval()`**: The `eval()` function is dangerous as it executes arbitrary code, making it vulnerable to injection attacks. If necessary, scrutinize the input rigorously.

#### 3. **Input Validation**

* **Whitelisting**: Implement a whitelist of acceptable characters or strings, rejecting all others. This limits the input to known safe values.
* **Blacklisting**: Avoid blacklisting as it's ineffective; attackers can easily bypass it with various techniques.
* **Client-Side Validation**: While useful for user experience, client-side validation is not secure as attackers can bypass it using proxies or other tools.

#### 4. **Defense in Depth**

* Use multiple layers of defense, such as combining input validation with output encoding. This increases the chances of catching any potential security flaws.

#### 5. **Use Proven Libraries**

* Avoid writing custom functions for encoding or validation. Instead, use established libraries that have been tested and are widely used in the industry.

#### 6. **Framework Implementation**

* Centralize your validation and encoding logic in a framework to ensure consistent and thorough protection across your application.
