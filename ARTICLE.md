# Write code that is easy to delete, not easy to extend. 
## - by tef

[Write code that is easy to delete, not easy to extend. --link](https://programmingisterrible.com/post/139222674273/write-code-that-is-easy-to-delete-not-easy-to?source=post_page-----56b0d9de2c43---------------------------------------)

This article challenges one of software engineering's most persistent assumptions: that code reusability is what's always good. The author argues that optimizing for ***deletability*** rather than *extensibility* leads to more maintainable systems, reframing lines of code as "lines spent" rather than "lines produced". They systematically walk through the architectural patterns that support this philosophy, from strategic copy-pasting to layered API design to deliberate coupling decisions. The piece demonstrates through concrete examples (HTTP error codes, Erlang supervision trees, the requests/urllib3 split) how separating what changes from what doesn't can create systems that can actually evolve over time.

The tension between making code pleasant to use and making it easy to change is something I've run into consistently, and this article offers a framework for managing those trade-offs without getting trapped by premature optimization or sunk cost fallacies.

---
### Proof-reading
Article checked for typos
### Comment Nadja Kaludjerovic
I found this article very interesting because it challenged one of the 
most prominent beliefs in computer science. I especially liked that you 
included concrete examples from the article, such as HTTP error codes, 
Erlang supervision trees and the requests/urllib3 split, which made the 
ideas more concrete and easier to understand. I also liked that you 
shared your personal experience of having to balance writing code that is 
pleasant to use while still being easy to modify and maintain.

### Comment Rujul Malhotra
The article provides an important take on coding practices. It was interesting to reflect on how we often place too much emphasis on efficiency and tight coupling between logic and functionality, which can make code harder to revisit and change. In an iterative software development process, prioritizing code that’s easier to change or delete seems much more valuable.

