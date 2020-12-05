# Markdown

## Headings

### Third Level Header

#### Fourth Level Header

```
# Markdown

## Headings

### Third Level Header

#### Fourth Level Header
```
<br>

## Markup

We can use *italics*, **bold**, `code`.

Paragraphs are separated by at least one empty line.

Force line break with two spaces in the end of this line.  
Here's the expected new line.

---
That was a horizontal rule.

```
We can use *italics*, **bold**, `code`.

Paragraphs are separated by at least one empty line.

Force line break with two spaces in the end of this line.  
Here's the expected new line.

---
That was a horizontal rule.
```
<br>

## Lists

- unordered first item
- second item
  - sub item
    1. ordered item
    1. item 2
- third item
- forth item

```
- unordered first item
- second item
  - sub item
    1. ordered item
    1. item 2
- third item
- forth item
```

### Definition Lists

<dl>
  <dt>term</dt>
  <dd>explanatory text</dd>
  <dt>another term</dt>
  <dd>explanation</dd>
</dl>

```
<dl>
  <dt>term</dt>
  <dd>explanatory text</dd>
  <dt>another term</dt>
  <dd>explanation</dd>
</dl>
```
<br>

## Links

This is an [example link](https://example.com).

```
This is an [example link](https://example.com).
```
<br>

## Code Blocks

### Output

``` emacs-lisp
;; Formatted block of code or text.
(defun sum (a b)
  (+ a b))
```

``` rust
fn main() {
  println!("Example");
}
```

    fn main() {
      println!("Example");
    }

### Markup

    ``` emacs-lisp
    ;; Formatted block of code or text.
    (defun sum (a b)
      (+ a b))
    ```

    ``` rust
    fn main() {
      println!("Example");
    }
    ```

        fn main() {
          println!("Example");
        }
<br>

## Tables

 Name | Phone | Age |
------|-------|-----|
Peter | 555   | 23  |
Alice | 2222  | 33  |
Tom   | 77777 | 66  |


Name|Phone|Age
-|-|-
Peter | 555| 23
Alice   |2222  | 33
Tom||| 

```
 Name | Phone | Age |
------|-------|-----|
Peter | 555   | 23  |
Alice | 2222  | 33  |
Tom   | 77777 | 66  |


Name|Phone|Age
-|-|-
Peter | 555| 23
Alice   |2222  | 33
Tom||| 
```

<br>
More details at https://daringfireball.net/projects/markdown/basics
