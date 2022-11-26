# stringValidator

Methods for validating a string.
Useful for validating text fields
in forms or other types of dynamic text data.

**Kind**: global class

- [stringValidator](#stringvalidator)
    - [stringValidator.hasAlphabet(string) ⇒](#stringvalidatorhasalphabetstring-)
    - [stringValidator.hasNumber(string) ⇒](#stringvalidatorhasnumberstring-)
    - [stringValidator.hasSpace(string) ⇒](#stringvalidatorhasspacestring-)
    - [stringValidator.hasChar(string) ⇒](#stringvalidatorhascharstring-)
    - [stringValidator.hasCharSep(string) ⇒](#stringvalidatorhascharsepstring-)
    - [stringValidator.isEmpty(string) ⇒](#stringvalidatorisemptystring-)
    - [stringValidator.onlyAlphabet(string) ⇒](#stringvalidatoronlyalphabetstring-)
    - [stringValidator.onlyNumber(string) ⇒](#stringvalidatoronlynumberstring-)
    - [stringValidator.onlyChar(string) ⇒](#stringvalidatoronlycharstring-)
    - [stringValidator.isEmail(email) ⇒](#stringvalidatorisemailemail-)
    - [stringValidator.truncate(text, wordCount) ⇒](#stringvalidatortruncatetext-wordcount-)

### stringValidator.hasAlphabet(string) ⇒

**Kind**: instance method of [<code>stringValidator</code>](#stringValidator)

**Returns** <code>true</code> if there is at
least one alphabet in a string

| Param  | Type                |
| ------ | ------------------- |
| string | <code>String</code> |

### stringValidator.hasNumber(string) ⇒

**Kind**: instance method of [<code>stringValidator</code>](#stringValidator)

**Returns** <code>true</code> if there
is at least one number in a string

| Param  | Type                |
| ------ | ------------------- |
| string | <code>String</code> |

### stringValidator.hasSpace(string) ⇒

**Kind**: instance method of [<code>stringValidator</code>](#stringValidator)

**Returns** <code>true</code> if there is a blank space,
tab or line break anywhere in a string

| Param  | Type                |
| ------ | ------------------- |
| string | <code>String</code> |

### stringValidator.hasChar(string) ⇒

**Kind**: instance method of [<code>stringValidator</code>](#stringValidator)

**Returns** <code>true</code> if there is at least
one special character in a string

| Param  | Type                |
| ------ | ------------------- |
| string | <code>String</code> |

### stringValidator.hasCharSep(string) ⇒

**Kind**: instance method of [<code>stringValidator</code>](#stringValidator)

**Returns** <code>true</code> if there is at least one special character in a string except dash(-) and underscore( \_ )

| Param  | Type                |
| ------ | ------------------- |
| string | <code>String</code> |

### stringValidator.isEmpty(string) ⇒

**Kind**: instance method of [<code>stringValidator</code>](#stringValidator)

**Returns** <code>true</code> if a string is empty
or contains only blank spaces

| Param  | Type                |
| ------ | ------------------- |
| string | <code>String</code> |

### stringValidator.onlyAlphabet(string) ⇒

**Kind**: instance method of [<code>stringValidator</code>](#stringValidator)

**Returns** <code>true</code> if a string
contains only alphabets

| Param  | Type                |
| ------ | ------------------- |
| string | <code>String</code> |

### stringValidator.onlyNumber(string) ⇒

**Kind**: instance method of [<code>stringValidator</code>](#stringValidator)

**Returns** <code>true</code> if a string
contains only numbers

| Param  | Type                |
| ------ | ------------------- |
| string | <code>String</code> |

### stringValidator.onlyChar(string) ⇒

**Kind**: instance method of [<code>stringValidator</code>](#stringValidator)

**Returns** <code>true</code> if a string
contains only special characters

| Param  | Type                |
| ------ | ------------------- |
| string | <code>String</code> |

### stringValidator.isEmail(email) ⇒

**Kind**: instance method of [<code>stringValidator</code>](#stringValidator)

**Returns** <code>true</code> if a string matches
the email format

| Param | Type                |
| ----- | ------------------- |
| email | <code>String</code> |

### stringValidator.truncate(text, wordCount) ⇒

**Kind**: instance method of [<code>stringValidator</code>](#stringValidator)

**Returns**: truncated text with '...' at the end.

| Param     | Type                |
| --------- | ------------------- |
| text      | <code>String</code> |
| wordCount | <code>Number</code> |
