Table of Contents
- [Vocab](#vocab)
- [Important blocks](#important-blocks)
- [On the AP Exam](#on-the-ap-exam)
- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)
  - [Headings](#headings)
  - [Text Formatting](#text-formatting)







## Vocab
<details>
  <summary>Abstraction</summary>
    The most fundamental idea in computer science, giving a name to something in a program to make it more readable.
</details>

<details>
  <summary>Procedural abstraction</summary>
    Using a procedure to name an idea, ex. the procedure "who" to the idea of picking an item from the list of people or cats.
</details>

<details>
  <summary>Transparency</summary>
  The transparency of an image is how much you can see what's behind it. For example, here is the Alonzo sprite shown with three different transparencies (which have been set using the ghost effect block).<img width="480" height="237" alt="transparency2" src="https://github.com/user-attachments/assets/57240fcf-fe01-4c66-b337-52dfbc4a5b01" />
</details>

<details>
  <summary>Expression</summary>
  An expression is a either a constant value (such as "4" or "winter") or a call to a reporter block including its inputs (such as<img width="201" height="33" alt="5+(4x3)" src="https://github.com/user-attachments/assets/59f88d10-4a88-42a7-8162-144fabd129c4" />,
<img width="85" height="22" alt="number" src="https://github.com/user-attachments/assets/c8e4e12a-ebe5-4726-ab61-72561bfe9be9" />,
  or<img width="351" height="28" alt="join-who-doeswhat-who" src="https://github.com/user-attachments/assets/578471d0-56d1-4039-9d7e-6747fb230474" /> ).
Expressions are evaluated to produce a single value (a value can be a number, a string, a sprite, a costume, a script, a list—anything). For example, <img width="201" height="33" alt="5+(4x3)" src="https://github.com/user-attachments/assets/1b47ef84-20fc-42c8-886b-9798d5466a84" /> will be evaluated to 17.
</details>

<details>
  <summary>Procedures</summary>
  A procedure is a named sequence of instructions that may take inputs and may report a value. Some languages call procedures methods or functions. Here are two types of procedures you have seen in Snap!
</details>

<details>
  <summary>Reporters</summary>
  Reporters have an oval shape. They report a value.
  <img width="212" height="27" alt="pick-random-empty-full-size" src="https://github.com/user-attachments/assets/564a2a9b-f412-4178-b17d-a0ee8cd876ca" />
</details>

<details>
  <summary>Commands</summary>
  Commands have a jigsaw puzzle shape. They tell the computer to do something without reporting a value.
  <img width="147" height="37" alt="broadcast" src="https://github.com/user-attachments/assets/b9680ba7-70df-42dd-99b6-f0aa5413e91b" />
</details>

<details>
  <summary>List</summary>
  A list is an ordered sequence of items. You've seen this example:
  <img width="496" height="169" alt="list-from-who-result" src="https://github.com/user-attachments/assets/d65a6b9b-79be-4733-b01a-a9da6cffbbc3" />
</details>

<details>
  <summary>Strings</summary>
  The items of this list are strings. A string is a sequence of characters (letters, digits, punctuation, etc.). A substring is just a piece of some existing string. For example, "Hanna," "anna", and "nnah" are each substrings of the string "Hannah." (The empty string as well as the original string are both also substrings.)
</details>

<details>
  <summary>Concatenation</summary>
  To concatenate strings means to make a bigger string by connecting two or more smaller strings. In Snap!, the <img width="116" height="27" alt="join()()" src="https://github.com/user-attachments/assets/8cfc2d42-c1fd-4343-8bd5-0800d4d37c50" />block lets you concatenate strings.
</details>

<details>
 <summary>Algorithm</summary>
  An algorithm is a sequence of steps that are usually performed by a computer. The algorithm doesn't have to be written in any particular programming language or even in a programming language at all; you can write your algorithm in English or any other human language.
</details>

<details>
  <summary>Pseudocode</summary>
  Some people call an algorithm written in human language pseudocode. Once you know the steps that the computer will take, you can code your algorithm in the programming language of your choice.
What's the purpose of "pseudocode"? Why write an algorithm vaguely in English when you could write it precisely in Snap!? If you were programming in a punctuation-heavy language, designing your program in pseudocode would help you focus on the important ideas instead of on details like quotation marks and semicolons. But pseudocode isn't as necessary with a language like Snap!, and pseudocode can make it easy for you to fall into wishful thinking about what the computer is capable of (such as writing "Pick tomorrow's winning lottery numbers" or "Here's the melody; write the harmony").
</details>

<details>
  <summary>Parameter</summary>
  A parameter (or formal parameter) is the input name, such as number of branches. The input name is set in the block definition. It never changes.<img width="600" height="223" alt="example-parameter" src="https://github.com/user-attachments/assets/c197a8f3-ea99-4fc7-a75d-575a78ac424d" />
</details>

<details>
  <summary>Argument</summary>
  An argument (or actual argument) is the input value, such as 6 for a hexagonal pinwheel. The input value is given each time the block is run; it can be a different value each time.<img width="331" height="36" alt="example-argument" src="https://github.com/user-attachments/assets/848c1d43-6d35-4d8b-8b2e-09871909e62f" />We use the word "input" both for parameters (input names) and for arguments (input values).
</details>

<details>
  <summary>Personally Identifiable Information (PII)</summary>
  Information that can identify you as an individual is called personally identifiable information (PII). It includes details that could reveal who you are—such as your Social Security number, age, race, phone number(s), medical information, financial information, or biometric data like a thumbprint or face scan.
</details>








## Important Blocks
<details>
  <summary>broadcast</summary>
     Sends a message to all the sprites. To set the message, click the down arrow and select "new..."
</details>

<details>
  <summary>when I receive</summary>
     (Click help on the block to learned more about it in order to complete this definition)
</details>





## On the AP Exam
<img width="1006" height="120" alt="image-2" src="https://github.com/user-attachments/assets/17476633-14c8-4c2e-af40-3f61c8655215" />

  - Many languages (and the AP CS Principles Exam) use return instead of report as the name of the command to give a value back at the end of a function call.
  - The exam uses "value of a procedure" to mean the value the procedure returns when called. For example, "the value of double(5)" means 10.



















































## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  

This ensures your notes are easy for you (and others) to read later.

---

## Headings

**When to use:** Organize your notebook into sections (like days, topics, or projects).  

- `#` for the notebook title (use once at the top).  

- `##` for each day or major topic.  

- `###` for subsections (like "Notes", "Practice", "Reflections").  

# Example:

# My Coding Notebook

## Day 1

### Notes

### Practice

# Text Formatting

When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

# Example:

**Class** = a blueprint for objects  

*Remember:* always test your code  

Use `System.out.println()` to print

 

# Code Blocks

When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

# Example:

```java

public class Hello {

    public static void main(String[] args) {

        System.out.println("Hello World!");

    }

}

```

# Lists

When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

# Example:

Define the class
Write the main method
Test your program
Variables

- Loops

- Conditionals

 

# Checklists

When to use: Track progress on assignments or tasks.

# Example:

[x] Complete coding warm-up

- [ ] Finish project draft

- [ ] Reflect on learning

 

# Blockquotes

When to use: Call out notes, reminders, or teacher comments.

# Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

# Tables

When to use: Compare values, track progress, or organize data neatly.

# Example:

| Task        | Status   | Notes          |

|--------------|------------|-----------------| 

| Homework 1  | Done #  | Submitted      |

| Homework 2  | Pending  | Needs review   |

 

# Links & Images

When to use: Add references, resources, or visuals.

# Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

To make an image that is a link, paste the image, then add the following before it, replacing website address with the link:

<a href="website address">

And after the image info, add: </a>

# Collapsible Sections

When to use: Hide solutions, extended notes, or extra details.

# Example:

<details>

  <summary>Click to reveal solution</summary>

  

System.out.println("Answer: 42");

</details>

 

# Footnotes

When to use: Add references or side notes without cluttering the page.

# Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

# Style Rules

Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

 

# Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.
