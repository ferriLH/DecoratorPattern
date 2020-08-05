# Decorator Pattern
Encoding and compression Decorator

## Java Class : 

* DataSource.java : A common data interface, which defines read and write operations
* FileDataSource.java : Simple data reader-writer
* DataSourceDecorator.java : Abstract base decorator
* EncryptionDecorator.java : Encryption decorator
* CompressionDecorator.java : Compression decorator
* Demo.java : Client code


## Output :

```
- Input ----------------
Name,Salary
John Smith,100000
Steven Jobs,912000
- Encoded --------------
Zkt7e1Q5eU8yUm1Qe0ZsdHJ2VXp6dDBKVnhrUHtUe0sxRUYxQkJIdjVLTVZ0dVI5Q2IwOXFISmVUMU5rcENCQmdxRlByaD4+
- Decoded --------------
Name,Salary
John Smith,100000
Steven Jobs,912000
```
