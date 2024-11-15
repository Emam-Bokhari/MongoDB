### 1. MongoDB Aggregate operators

<table>
  <thead>
    <tr>
      <th>Operator/Command</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>$match</code></td>
      <td>Filters documents based on specified criteria.</td>
    </tr>
    <tr>
      <td><code>$project</code></td>
      <td>Specifies fields to include, exclude, or modify in the output.</td>
    </tr>
    <tr>
      <td><code>$addFields</code></td>
      <td>Adds new fields to documents in the pipeline.</td>
    </tr>
    <tr>
      <td><code>$out</code></td>
      <td>Writes the aggregation result to a new collection.</td>
    </tr>
    <tr>
      <td><code>$merge</code></td>
      <td>Merges aggregation results into an existing collection.</td>
    </tr>
    <tr>
      <td><code>$group</code></td>
      <td>Groups documents by a specified field, allowing aggregate calculations.</td>
    </tr>
    <tr>
      <td><code>$sum</code></td>
      <td>Calculates the sum of numeric values in a group.</td>
    </tr>
    <tr>
      <td><code>$avg</code></td>
      <td>Calculates the average of numeric values in a group.</td>
    </tr>
    <tr>
      <td><code>$min</code></td>
      <td>Finds the minimum value within a group.</td>
    </tr>
    <tr>
      <td><code>$max</code></td>
      <td>Finds the maximum value within a group.</td>
    </tr>
    <tr>
      <td><code>$push</code></td>
      <td>Adds values to an array within a group.</td>
    </tr>
    <tr>
      <td><code>$$ROOT</code></td>
      <td>Refers to the entire document being processed in an aggregation stage.</td>
    </tr>
    <tr>
      <td><code>$unwind</code></td>
      <td>Deconstructs an array field, outputting one document per array element.</td>
    </tr>
    <tr>
      <td><code>$bucket</code></td>
      <td>Categorizes documents into specified ranges or "buckets."</td>
    </tr>
    <tr>
      <td><code>$sort</code></td>
      <td>Sorts documents in ascending or descending order.</td>
    </tr>
    <tr>
      <td><code>$limit</code></td>
      <td>Restricts the number of documents passed to the next stage.</td>
    </tr>
    <tr>
      <td><code>$facet</code></td>
      <td>Processes multiple aggregation pipelines within a single stage.</td>
    </tr>
    <tr>
      <td><code>$lookup</code></td>
      <td>Performs a left outer join to merge data from two collections.</td>
    </tr>
    <tr>
      <td><code>CollScan</code></td>
      <td>Performs a collection scan to retrieve documents without an index.</td>
    </tr>
    <tr>
      <td><code>IndexScan</code></td>
      <td>Performs an index scan, retrieving documents using an index.</td>
    </tr>
    <tr>
      <td><code>TextScan</code></td>
      <td>Performs a text search scan to match documents containing specified text.</td>
    </tr>
  </tbody>
</table>
