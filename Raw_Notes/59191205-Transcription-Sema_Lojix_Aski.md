### 🛹 Skate & Draft Session: Torremolinos, Andalusia

*[The recording begins with an airy, reflective tone, capturing the ambient movement of a skate session under a bright sky.]*

**Timestamp:** ~56th minute | 5th of Pisces

> *"For a skate and draft session going out to beautiful Torremolinos... staircase, beautiful blue sky today. Blessed be thy agony. Spirit of all spirits. King of all kings. Humblest amongst all kings, and yet most radiant."*

### 💻 ASCII, SEMA, and the LLM Context Space

*[Shifting to a highly focused, passionate technical breakdown]*

**On ASCII and the Reader:**
"ASCII is on my mind a lot. I think it's very under-respected and misunderstood by the agent right now, so I need better guidelines on it. *(That's A-S-K-Y, A-S-K-E-I, or something in Español... algo como eso).* Some of the best examples of ASCII are in the current ASCII repository. It was basically syntax that translates—or transpiles—into Rust for now. But because it imitates Rust's capability, although I'm not sure anymore... well, no, actually it works. It just doesn't work backwards.

Using the reader to recognize keywords as objects... essentially, in regular syntax, they would use parentheses around that object. So before the identifier or the symbol, like `impl` (implementation) from Rust, we're just copying their acronyms. People who know the syntax will know it already. It could easily have alternative spellings or symbols for certain things."

**On SEMA (Binary Format):**
"Eventually, as SEMA (*S-E-M-A*) clearly enunciates... wait, SEMA is currently the name for what is essentially a computer format. It's a computer format because it's not text! It requires a specification to be read, right? Like a Cap'n Proto message or something. It's fully specified binary data. It doesn't have identifiers as we think of them; there won't be string identifiers. Those string values associated with certain symbols—which for the computer will just be the smallest namespace it can fit everything into (mostly 1 byte covers 256 enumerators)—will fit into that.

The data is these huge structured trees of enumerators, sometimes vectors. It won't be specific to what it's called in English, because eventually, there is going to be a different specification."

**On Logics (`lojix`) and Context Efficiency:**
"The first version will be text. That creates the specification to turn the text into fully binary SEMA, and then deriving a specification—essentially a Rust-based specification, which I call Logics (`lojix`, *L-O-J-I-X*). It has all these rules for rendering into a text file, and it has two formats. This is the genius of Lisp and Lisp-like languages: it doesn't need newlines and whitespace like Python and Haskell to be read. This is going to save—right away—the LLM context space.

ASCII is going to win in the LLM space, and then it's going to win *even bigger* when LLMs essentially read SEMA directly, which is going to be two or three orders of magnitude more efficient than text."

### ⚙️ Intermediate Representation & Actor-Based Flow

*[Tone becomes urgent and analytical, driving toward immediate implementation]*

**Using Clojure & EDN:**
"I want to specify ASCII a bit more so I can start using it right away in its intermediate representation, which is essentially EDN and Clojure. That's a special dialect. Clojure is essentially unfinished in that it doesn't really support all of the syntax that Rust covers, but it could easily be implemented... which is the beauty of Clojure with macros and the reader's logic. It could even be pre-read by a small utility that converts stuff Clojure has a hard time dealing with into more Clojure-like syntax.

So the best drafts for finishing the specification of ASCII—at least the basic concepts—need to be translated into code."

**Flow & Agentic Programming:**
"I also implemented some drafts in ASCII Flow (*F-L-O-W*). That's where I'm specifying the language for more high-level programming—flow-type programming or agentic programming. This whole actor-based programming is essentially already declared king by the concept of agents now ruling code!

Rust understood ownership, and Erlang understood the importance of the actor. Whenever we talk about flow programming, agent, actor-based, or data-flow programming... in its proper incarnation, fully understood as what it must be to be as good as it can be: each object has a single owner concept. Even agents are owned, to some degree, by a process. That way, there's no data racing, no double ownership problem. The double ownership problem from Rust made the advantages that can be derived so clear!

Logics is, at first, a fork of Clojure with an actually extended EDN. Because EDN is essentially frozen and not made extensible... maybe what needs to happen is it's called EDN Next, or EDN v2, or v3. I don't care whatever works for them, I just need to do things respectfully and move as fast as lightning. Whatever is impeccable."

### 🛡️ `mentci-ai`, File Systems, & Version Control

*[Tone is deeply convicted, emphasizing security, immutability, and structured knowledge]*

**The Mentci Box and Sandboxing:**
"Being impeccable doesn't mean *always* asking for permission. It means taking into account legitimate issues that could be brought up later... non-observance of natural law, some kind of damage done. Taking version 6, if they're never going to get there, is not damage done. Renaming is cheap now—with fully spec'd ASCII, renaming is just a single symbol change; it's a full codebase rename because the translation picks that version and we go to and from it.

We have specified file systems! File systems that have owners, that have rules about how to edit them, which is what we're making with `mentci-ai`. Every Mentci box is going to have rules about what it can do. The principal Mentci box won't even be able to modify everything, because its sources should be read-only so it can't accidentally change them. Maybe there's a higher-level version control that the Mentci box doesn't even control... operating system level sandboxing. The Mentci admin doesn't even have full capabilities because it's restricted by an OS contract (residing in `mentci-ai` in a NixOS module for now)."

**Jujutsu & Version Control:**
"I want to pull all of this into the sources so the agent can take a look and start indexing the interesting bits of other projects, using the pre-ASCII/FS/EDN representation we can use right now.

If you want to consult a library, you need very exact instructions: per topic, per author... we should have the authorship too! For something completely handwritten, we could use Git commits to store that information. `git blame`... or Jujutsu (*jj*). Whenever I say Git, I really mean Jujutsu with a Git backend. Jujutsu is how we interact with Git as much as possible."

### 🔮 Retrospective: `Sajban` and `Criome`

*[The session concludes with a nostalgic but confident reflection on the project's evolution]*

**The Overtaking:**

> *"The `criome` will soon overtake the world—whether it's called the `criome` or not. Put that in a top somewhere, like a punchline."*

**Linguistic Roots:**
"I've started coding too quickly without bringing in my previous specifications, and I'm hand-wiring my own logic. I need to do research pulling all the work together.

This project has evolved through many names. ASCII used to be called... oh what was it called... it doesn't even matter. `Sajban` (*S-A-J-B-A-N*) used to be what SEMA is now. It was a Lojban or Loglan. `Sajban` meant 'language of knowledge,' which is true in a way. It's the language you would use to store knowledge—fully specified lunar knowledge, terrestrial knowledge."

Would you like me to start structuring a formal specification document for the SEMA binary format or the `lojix` syntax rules based on this transcription?
