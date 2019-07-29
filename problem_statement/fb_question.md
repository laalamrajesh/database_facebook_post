Consider a typical Facebook post shown in the picture (in the same folder)

Create a relational database schema to store all the data related to the post

In this version of a "Facebook Post”,
- Ignore few features like Privacy of the post, Post Sharing related info.
- Ignore friendships between users
- Assume we support only one level of replies for comments i.e. replies to a reply are also considered as reply to a comment.
- Assume posts and comments only have text content.
- You need not store additional information about Post Content like @mentions, #hastags, URLs etc.
- Assume that a user cannot have multiple reactions to the same post or comment

Define your schema in the format given below (in a text file)

BankAccount Table

- account no (char) (PK)
- account holder name (char)
- branch (FK to BranchName table)
- home address (char)

BranchName Table

- id (int) (PK)
- IFSC Code (char)
- branch address (char)

PS: PK stands for Primary Key, FK stands for Foreign Key
