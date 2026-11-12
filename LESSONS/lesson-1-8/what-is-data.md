TOPIC: WHAT IS DATA?

> Data is information represented in a form a computer can store, move, and process.

* How It Works: Data Represents Something Real
Here's a detail that's easy to skim past but genuinely matters: data isn't the thing itself. It's a representation of the thing.

When a school system stores a student's grade, it isn't storing the student. It's storing a number, or a letter, that stands in for a fact about the student. When a banking app shows your balance, it isn't showing you a pile of physical cash — it's showing a number that represents how much money the bank's records say you have.

This matters because it explains a lot of what programming is actually about: deciding how to represent real-world things as data the computer can work with.

Consider a customer in an online store. In real life, a customer is a whole person — they have a name, a history, preferences, moods, a physical address. The program doesn't need all of that, and it can't capture all of that. It needs the parts that are relevant to the task:

-Name (so the order can be labeled)
-Email (so a receipt can be sent)
-Shipping address (so the package can be delivered)
-Everything else about that person — their sense of humor, what they had for breakfast — isn't part of the data, because the program has no use for it.

This is the first real design decision most programmers make, often without noticing they're making it: choosing which facts about the real world are worth turning into data, and which aren't.