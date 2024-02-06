# Asynchronous Programming in Rust	

<a href="https://www.packtpub.com/product/asynchronous-programming-in-rust/9781805128137"><img src="https://content.packt.com/B20892/cover_image_small.jpg" alt="no-image" height="256px" align="right"></a>

This is the code repository for [Asynchronous Programming in Rust](https://www.packtpub.com/product/asynchronous-programming-in-rust/9781805128137), published by Packt.

**Learn asynchronous programming by building working examples of futures, green threads, and runtimes**

## What is this book about?
Explore the nuances of transitioning from high-level languages to Rust with this book. Navigate potential frustrations arising from differences in modeling asynchronous program flow and recognize the need for a fundamental understanding of the topic.

This book covers the following exciting features:
* Explore the essence of asynchronous program flow and its significance
* Understand the difference between concurrency and parallelism
* Gain insights into how computers and operating systems handle concurrent tasks
* Uncover the mechanics of async/await
* Understand Rust’s futures by implementing them yourself
* Implement green threads from scratch to thoroughly understand them

If you feel this book is for you, get your [copy](https://www.amazon.com/Asynchronous-Programming-Rust-asynchronous-programming/dp/1805128132/ref=sr_1_1?crid=2NQEFXDPADDSG&keywords=asynchronous+programming+in+rust&qid=1707141670&sprefix=asynchronous+programming+in+r%2Caps%2C313&sr=8-1) today!

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
pub trait Future {
type Output;
fn poll(&mut self) -> PollState<Self::Output>;
}

```

**Following is what you need for this book:**

This book is for programmers who want to enhance their understanding of asynchronous programming, especially those experienced in VM’ed or interpreted languages like C#, Java, Python, JavaScript, and Go. If you work with C or C++ but have had limited exposure to asynchronous programming, this book serves as a resource to broaden your knowledge in this area.
Although the examples are predominantly in Rust, the intricacies of Rust’s futures are covered in detail. So, anyone with a keen interest in learning Rust or with working knowledge of Rust will be able to get the most out of this book.

With the following software and hardware list you can run all code files present in the book (Chapter 1-10).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-10 | Rust (version 1.51 or later) | Windows, macOS, or Linux |


### Related products
* Hands-On Concurrency with Rust [[Packt]](https://www.packtpub.com/product/hands-on-concurrency-with-rust/9781788399975) [[Amazon]](https://www.amazon.com/Hands-Concurrency-Rust-Confidently-memory-safe/dp/1788399978/ref=sr_1_1?crid=1S3COJO6XGV3Z&keywords=Hands-On+Concurrency+with+Rust&qid=1707141930&sprefix=hands-on+concurrency+with+rust%2Caps%2C291&sr=8-1)

* Hands-On Microservices with Rust [[Packt]](https://www.amazon.com/Hands-Microservices-Rust-scalable-microservices/dp/1789342759/ref=sr_1_1?crid=29U7MSUFK21FC&keywords=Hands-On+Microservices+with+Rust&qid=1707141998&sprefix=hands-on+concurrency+with+rust%2Caps%2C863&sr=8-1) [[Amazon]](https://www.amazon.com/Hands-Microservices-Rust-scalable-microservices/dp/1789342759/ref=sr_1_1?crid=29U7MSUFK21FC&keywords=Hands-On+Microservices+with+Rust&qid=1707141998&sprefix=hands-on+concurrency+with+rust%2Caps%2C863&sr=8-1)

## Get to Know the Author
**Carl Fredrik Samson** is a popular technology writer and has been active in the Rust community since 2018. He has an MSc in Business Administration where he specialized in strategy and finance. When not writing, he’s a father of two children and a CEO of a company with 300 employees. He’s been interested in different kinds of technologies his whole life and his programming experience ranges from programming against old IBM mainframes to modern cloud computing, using everything from assembly to Visual Basic for Applications. He has contributed to several open source projects including the official documentation for asynchronous Rust.
