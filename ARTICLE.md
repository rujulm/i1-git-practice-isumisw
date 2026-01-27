# Write code that is easy to delete, not easy to extend. 
## - by tef

[Write code that is easy to delete, not easy to extend. --link](https://programmingisterrible.com/post/139222674273/write-code-that-is-easy-to-delete-not-easy-to?source=post_page-----56b0d9de2c43---------------------------------------)

This article challenges one of software engineering's most persistent assumptions: that code reusability is what's always good. The author argues that optimizing for ***deletability*** rather than *extensibility* leads to more maintainable systems, reframing lines of code as "lines spent" rather than "lines produced". They systematically walk through the architectural patterns that support this philosophy, from strategic copy-pasting to layered API design to deliberate coupling decisions. The piece demonstrates through concrete examples (HTTP error codes, Erlang supervision trees, the requests/urllib3 split) how separating what changes from what doesn't can create systems that can actually evolve over time.

The tension between making code pleasant to use and making it easy to change is something I've run into consistently, and this article offers a framework for managing those trade-offs without getting trapped by premature optimization or sunk cost fallacies.

---
### Proof-reading
Article checked for typos

