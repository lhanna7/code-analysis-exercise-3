# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (animal){
  const normalizedName = animal.toLowerCase()

  if (normalizedName === "alligator"){
    return "small"
  } else {
    return "wide"
  }
}
```

| Input | Output |
| ----- | ------ |
|  cat  |  wide  | 
|alligator| small | 
|  dog  |  wide  | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program takes the input, animal, and assigns a new name in all lowecase- called normalizedName. Then, the next function chekcs if normalizedName matches alligator. If alligator===alligator, then the output will return small. If anyotheranimal===alligator, then the output will return wide.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
