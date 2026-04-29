Software Design and Modeling
3.3 State Diagrams
State Diagram 1 – Book Lifecycle

This state diagram represents the lifecycle of a book within the system.

Initially, a book is in the "Available" state, meaning it is ready to be borrowed by a user. When a user borrows the book, its state changes to "Borrowed", indicating that it is currently checked out and not accessible to others.

From the borrowed state, two possible transitions can occur. The user may return the book, which brings it back into the system and makes it available again. Alternatively, the book may be reported as lost, in which case its state changes to "Lost" and it is no longer part of the active inventory.

This diagram helps track the availability and status of books and ensures proper management of borrowing operations within the system.

<img width="1900" height="935" alt="image" src="https://github.com/user-attachments/assets/3ad40fae-5ca4-4321-b538-70bbcce43f2d" />

State Diagram 2 – Notes Lifecycle

This state diagram illustrates the lifecycle of student notes in the system.

The process begins with the "Draft" state, where a student is actively writing or editing notes. Once the student submits the notes, they transition into the "Pending review" state, where they await evaluation.

At this stage, an administrator reviews the content and decides whether to approve or reject it. If approved, the notes move into the "Published" state, making them visible to other users. If rejected, the notes transition to the "Rejected" state, allowing the student to revise and resubmit them.

Over time, published notes may become outdated and are moved into the "Archived" state, where they are no longer actively used but still stored in the system.

This diagram ensures a clear workflow for content creation, validation, and lifecycle management within the application.

<img width="1900" height="932" alt="image" src="https://github.com/user-attachments/assets/aa1cc898-b9e3-4870-a826-ac1c1a18704c" />
