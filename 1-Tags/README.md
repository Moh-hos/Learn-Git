## tags

Tags are resources that point to specific points in Git history
for example : (V1/0/1)

Tags are like branches that don't change.

Unlike branches, tags do not need a commit history after creation

##### Git supports two types of tags: `annotated` and `light weight`

Annotated and lightweight tags are different in terms of the meta data they store. The best way to use Git tags is to consider annotated tags as public and lightweight tags as private. Annotated tags store additional meta data such as tagger's name, email, and tag date. This data is important for public release. Lightweight tags are basically markups of a commit, they are just a name and a pointer to a commit that are useful for creating quick links to the corresponding commit.

### Conclusion

Tagging is typically used to create tags whose identifiers are created using semantic versioning, corresponding to software release cycles. The git tag command is the main part for working with tags, such as: creating, modifying and deleting tags that use this command. In this article, we found that tags are divided into two types: annotated and lightweight. Annotated tags are generally better to use because they store more valuable meta data about the tags than lightweight tags.
