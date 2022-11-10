# Progress Bar

# Days
.
.
.
## #58
- Core Data entity relationship types with examples. One-to-many, many-to-many, one-to-one, many-to-one.
- Setting up one-to-many relationship entity
- Managing other entity features, such as removing duplicates using `NSMergePolicy` and unwrapping conditionals by making `NSManagedObject` subclass.
- Workaround for `NSSet` type property, an old Objective-C data type equivalent to Swift's `Set`, which can not be used with SwiftUI's `ForEach`.
- Creating and displaying data on SwiftUI using `List`, `ForEach` and `Section`.

## #59
- Takeaways from Core Data review:
1. Core data is available on all of Apple's platforms
2. We can generate code for Core Data entity on XCode, by simply adjusting the Codegen property in the data model inspector
3. We can filter a fetch request using `NSPredicate`. For more complex predicates we can combine multiple instances of `NSPredicate` using `NSCompoundPredicate`
4. `NSPredicate` can have dynamic string values. `%K` placeholder goes for attribute while `%@` goes for value.
5. `NSManagedObject` subclasses automatically conform to the `Hashable` protocol.
6. We can specify single entity inside a fetch request. No multiple entities allowed.
7. It's good practice to check whether a managed object context has any changes before saving.
8. To ensure an attribute is unique, we can use constraints.