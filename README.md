The project has been refactored in accordance to the video. The changes are as follows:

- Methods were extracted from `Customer` and to `Rental` classes to increase reusability
- Code readability has been improved by variable renaming AND inlining
- Methods were moved to their appropriate classes (from `Customer` to `Rental`)
- Methods were also inlined for better performance and readability, certain parts of them were extracted to another methods (again, to increase reusability)
- Loops were replaced with streams