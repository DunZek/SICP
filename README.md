# Structure and Intepretation of Computer Programs

- Online book: <https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html>
- <http://mitpress.mit.edu/sicp> provides support to users:
    - Programs used in the book
    - Sample programming assignments.
    - Supplementary materials.
    - Downloadable implementations of the Scheme dialect of Lisp.
- Sample programming assignments: <https://mitpress.mit.edu/sites/default/files/sicp/psets/index.html>
- Code from the book: <https://mitpress.mit.edu/sites/default/files/sicp/code/index.html>
- Errata (Text-error corrections): <https://mitpress.mit.edu/sites/default/files/sicp/errata.html>
- Getting scheme:
	- MIT/GNU Scheme: <https://www.gnu.org/software/mit-scheme/>
	- MIT/GNU Scheme User's Manual: <https://www.gnu.org/software/mit-scheme/documentation/stable/mit-scheme-user.html>
	- MIT/GNU Scheme Reference: <https://www.gnu.org/software/mit-scheme/documentation/stable/mit-scheme-ref.html>

<br>

Foreword notes:
- Many things are programmed. Large problems are tackled via successive programming. Applications must perform well in the face of difficulty.
- The programmer will learn Lisp to understand the structure and interpretation of computer programs.
- Three principles:
    - Human mind
    - Collections of computer programs
    - The computer
- "If art interprets our dreams, the computer executes them in the guise of programs" - The exhilaration of programming.
- Your potential is limited by your capacity to understand the subject at hand.
- Out of the laws of physics arose and keeps arising ever increasing abstracted expressions of the underlying principles, touching the human mind.
- Algorithms are programs founded upon mathematical functions, whose optimization is measured through the parameters of execution time and data storage. Bear in mind the task of improving performance.
- Lisp and Fortran originate from two important areas of applications:
    - Fortran -> scientific and engineering computation.
    - Lisp -> artificial intelligence.
- Scheme is a dialect of Lisp and differs in several important ways:
    - Static scoping for variable binding
    - Permitting functions to yield functions as values
- Algol 60 is the ancestral language of Lisp and Pascal. The former differs from the latter in the extensibility of its underlying functionalities. Lisp's extensibility can be attributed to the "list", its native data structure. Pascal's requirement to specialize data structures limits extensibility. This allows Lisp to create exponentially more applications due to the "list", its dynamic data structure.
- SICP is a serious Lisp and programming book irregardless of who its readers are. Note that most Lisp books are used to prepare the reader for work in AI. However, through Lisp, there will be much overlap within the two disciplines of engineering and science.
- Tools and programming languages come about from the rise of software problems. AI is a no different source of cause. As the organization of software becomes paramount to realizing greater potential, languages arise to meet such needs. These programming languages become lesser and lesser primitive the nearer it and its underlying functionalities reach human comprehension. Lisp is a language written to be so simple in syntactical comprehension that parsing technologies act insignificantly.

2nd Edition Preface notes:
- The materials and principles of this book have been taught and implemented numerous and numerous times since they've formed the basis of MIT's entry-level computer science subject since 1980. The cores of new computer systems and languages were born out of the ideas students and readers of this material and text have taken.
- The program implementations of Scheme have been rewritten in this edition to conform the book to the IEEE Scheme standard (IEEE 1990) to run code.
- This new edition emphasizes several new themes:
    - Most important is the central role played by different approaches to dealing with time in computational models: objects with state, concurrent programming, lazy evaluation, and nondeterministic programming.
    - Sections of concurrency and nondeterminism have been expanded. Such themes are integrated throughout the book.
- Perhaps not all content will be covered. Perhaps only the first three or four chapters. Pick and choose if you wish in accordance to your needs.
- <http://mitpress.mit.edu/sicp> provides support to users:
    - Programs used in the book
    - Sample programming assignments.
    - Supplementary materials.
    - Downloadable implementations of the Scheme dialect of Lisp.

1st Edition Preface notes:
- This introductory computer-science subject is designed to reflect two major concerns:
    - Programming languages are formal mediums for expressing ideas about methodologies apart from their ability to simply perform operations. Thus, programs must first and foremost be humanly comprehensible.
    - The essence of the material is to teach the techniques used to control the intellectual complexity of large software systems. Controlling complexity enables the creation of more ambitious programs.
- Students who complete this subject should be adept programmers:
    - Having command of the techniques used to control complexity.
    - Being capable of reading 50-page long programs (when written in exemplary style).
    - Knowing which is meaningless in pursuit, and which is important to keep.
    - Confidence in altering and modifying programs in accordance to the spirit and style of their original author, and their underlying principles.
    - The skills taught are no different from any other engineering discipline:
        - Abstractions are used to control complexity by hiding unnecessary details.
        - Furthermore of such, conventional interfaces are used to enable programmers to construct systems by combining standard, well-understood pieces.
        - Furthermore of such, programming languages are designed to emphasize particular important features and to deemphasize irrelevant ones.
- Computer science is little about actual science and its significance is little about computers. What it encapsulates is a revolution in the way we think and express our ideas, the computer revolution, the essence of which may be best described as "*procedural epistemology*".
    - Procedural epistemology -> the study of the structure of knowledge from an imperative point of view, as opposed to the more declarative point of view taken by classical mathematical subjects.
        - Mathematics is the framework that answers "what is".
        - Computation is the framework that. answers "how to".

- The lack of complicated syntactic structure and ways of forming compound expressions allows Lisp-like languages to be learned effortlessly.
    - An hour is all it takes to teach formal properties.
    - Enabling programmers to forget syntactic details (due to its nonexistence) further enable them to tackle the issue at hand: what to compute and how to decompose problems into manageable parts.
- The design of Lisp allows programmers to use large-scale strategies for the modular decomposition of programs, all of which are embedded in an interactive environment that enables incremental program design, construction, testing, and debugging:
    - The creation of procedural and data abstractions.
    - Usage of higher-order functions to capture common patterns of usage.
    - Modelling local state using assignment and data mutation.
    - Linking parts of a program with streams and delayed evaluation.
    - Ability to implement embedded languages.
- The unprecedented power and elegance of Lisp is attributed to the generations of Lisp wizards throughout the times, starting with John McCarthy.
- Scheme, the dialect of Lisp used, is the attempt of combining the power (effectiveness) and elegance (efficiency) of Lisp and Algol.
	- From Lisp:
		- Simple syntax
		- Uniform representation of programs as data objects
		- Garbage-collected heap-allocated data
	- From Algol:
		- Lexical scoping
		- Block structure
