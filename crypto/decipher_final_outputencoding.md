<!-- YAML
added: v0.1.94
-->
* `outputEncoding` {string} 返回值的[字符编码][encoding]。
* 返回: {Buffer | string} 任何剩余的解密内容。 如果指定了 `outputEncoding`，则返回一个字符串。 如果未提供 `outputEncoding`，则返回 [`Buffer`]。

一旦 `decipher.final()` 方法被调用，`Decipher` 对象就不能再用于解密数据。
如果试图再次调用 `decipher.final()`，将会抛出一个错误。


