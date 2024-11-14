### 1. List of MongoDB operators

<table>

<thead>
<tr>
<th>Operator/Command</th>
<th>Description</th>
</tr>
</thead>

<tbody>
<tr>
<td><code>insertOne</code></td>
<td>Inserts a single document into a collection.</td>
</tr>

<tr>
<td><code>insertMany</code></td>
<td>Inserts multiple documents into a collection.</td>
</tr>

<tr>
<td><code>find</code></td>
<td>Retrieves documents that match the specified criteria.</td>
</tr>

<tr>
<td><code>findOne</code></td>
<td>Retrieves a single document that matches the specified criteria.</td>
</tr>

<tr>
<td><code>project</code></td>
<td>Specifies which fields to include or exclude from the result set.</td>
</tr>

<tr>
<td><code>$eq</code></td>
<td>Matches documents where the field is equal to the specified value.</td>
</tr>

<tr>
<td><code>$ne</code></td>
<td>Matches documents where the field is not equal to the specified value.</td>
</tr>

<tr>
<td><code>$gt</code></td>
<td>Matches documents where the field is greater than the specified value.</td>
</tr>

<tr>
<td><code>$gte</code></td>
<td>Matches documents where the field is greater than or equal to the specified value.</td>
</tr>

<tr>
<td><code>$lt</code></td>
<td>Matches documents where the field is less than the specified value.</td>
</tr>

<tr>
<td><code>$lte</code></td>
<td>Matches documents where the field is less than or equal to the specified value.</td>
</tr>

<tr>
<td><code>sort</code></td>
<td>Sorts the documents in the result set based on specified fields.</td>
</tr>

<tr>
<td><code>$in</code></td>
<td>Matches documents where the field’s value is in an array of specified values.</td>
</tr>

<tr>
<td><code>$nin</code></td>
<td>Matches documents where the field’s value is not in an array of specified values.</td>
</tr>

<tr>
<td><code>$and</code></td>
<td>Joins query clauses with a logical AND; returns documents that match all conditions.</td>
</tr>

<tr>
<td><code>$or</code></td>
<td>Joins query clauses with a logical OR; returns documents that match any condition.</td>
</tr>

<tr>
<td><code>$nor</code></td>
<td>Joins query clauses with NOR; returns documents that fail all conditions.</td>
</tr>

<tr>
<td><code>$not</code></td>
<td>Inverts the effect of a query expression; matches documents that do not satisfy it.</td>
</tr>

<tr>
<td><code>$exists</code></td>
<td>Matches documents where the specified field exists.</td>
</tr>

<tr>
<td><code>$type</code></td>
<td>Selects documents if a field is of the specified type.</td>
</tr>

<tr>
<td><code>$size</code></td>
<td>Matches any array with the specified number of elements.</td>
</tr>

<tr>
<td><code>$all</code></td>
<td>Matches arrays that contain all elements specified in the condition.</td>
</tr>

<tr>
<td><code>$elemMatch</code></td>
<td>Matches documents that contain an array field with at least one element matching all conditions.</td>
</tr>

<tr>
<td><code>$set</code></td>
<td>Updates the value of a field.</td>
</tr>

<tr>
<td><code>$addToSet</code></td>
<td>Adds a value to an array only if it does not exist in the array.</td>
</tr>

<tr>
<td><code>$each</code></td>
<td>Adds each element of a given array to an array field (typically used with $push or $addToSet).</td>
</tr>

<tr>
<td><code>$push</code></td>
<td>Adds a value to an array field.</td>
</tr>

<tr>
<td><code>$unset</code></td>
<td>Removes the specified field from a document.</td>
</tr>

<tr>
<td><code>$pop</code></td>
<td>Removes the first or last element of an array.</td>
</tr>

<tr>
<td><code>$pull</code></td>
<td>Removes all instances of a value from an array that match a specified condition.</td>
</tr>

<tr>
<td><code>$pullAll</code></td>
<td>Removes multiple instances of specified values from an array.</td>
</tr>

<tr>
<td><code>$</code> (positional operator)</td>
<td>Refers to the first matched element in an array field to update it.</td>
</tr>

<tr>
<td><code>$inc</code></td>
<td>Increments the value of a field by a specified amount.</td>
</tr>

<tr>
<td><code>deleteOne</code></td>
<td>Deletes a single document that matches the filter criteria.</td>
</tr>

<tr>
<td><code>drop</code></td>
<td>Deletes an entire collection.</td>
</tr>

</tbody>

</table>
