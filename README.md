# Refactoring-in-Java

<a href="https://www.packtpub.com/product/refactoring-in-java/9781805126638"> <img src="https://content.packt.com/B20912/cover_image_small.jpg" alt="Refactoring in Java" itemprop="url" height="256px" align="right">

This is the code repository for [Refactoring in Java](https://www.packtpub.com/product/refactoring-in-java/9781805126638), published by Packt.

**Improving code design and maintainability for Java developers**

## What is this book about?
This is a comprehensive guidebook for Java developers seeking to improve the quality, design, and maintainability of their codebase with the help of practical examples and case studies.

This book covers the following exciting features:
* Recognize and address common issues in your code
* Find out how to determine which improvements are most important
* Implement techniques such as using polymorphism instead of conditions
* Efficiently leverage tools for streamlining refactoring processes
* Enhance code reliability through effective testing practices
* Develop the skills needed for clean and readable code presentation
* Get to grips with the tools you need for thorough code examination
* Apply best practices for a more efficient coding workflow

If you feel this book is for you, get your [copy](https://amzn.eu/d/g2oaim3) today!

## Instructions and Navigations

The code will look like the following:

```
String userInput = getUserInput();
String sqlQuery = "SELECT * FROM users WHERE username = ?";
PreparedStatement preparedStatement = connection.
prepareStatement(sqlQuery);
preparedStatement.setString(1, userInput);
ResultSet resultSet = preparedStatement.executeQuery();
```

**Following is what you need for this book:**
This book is for Java developers, software architects, and technical leads looking for a comprehensive guide to advancing their skills in software design and refactoring. The book is ideal for experienced Java enthusiasts, quality assurance engineers, and codebase maintainers as it provides practical insights, real-world examples, and essential patterns. Development managers who want to foster clean coding practices by using best practices for efficient workflows will also find this book useful.

With the following software and hardware list you can run all code snippets present in the book (Chapter 1-9).

## Software and Hardware List
| Software required | OS required |
| ------------------------------------ | ----------------------------------- |
| Java 17 | Windows, MacOS, or Linux |
| Maven 3.8 | Windows, MacOS, or Linux |

## Related products
* Designing Hexagonal Architecture with Java [[Packt]](https://www.packtpub.com/product/designing-hexagonal-architecture-with-java-second-edition/9781837635115)   [[Amazon]](https://amzn.eu/d/3rkxz72)
* Persistence Best Practices for Java Applications [[Packt]](https://www.packtpub.com/product/persistence-best-practices-for-java-applications/9781837631278) [[Amazon]](https://amzn.eu/d/f6oPFB9)

## Get to Know the Author
**Stefano Violetta**
Stefano Violetta is a creative backend engineer, bringing over 15 years of experience in software development and architecture. He has worked in a diverse range of companies, spanning from startups to industry giants like eBay. Stefano takes pride in crafting meticulously written code to build sophisticated applications that align with their intended purpose, ensuring functionality and meeting the precise needs of users. Or at least, he tries to! Beyond the world of software, Stefano enjoys immersing himself in reading and watching movies during his free time.








