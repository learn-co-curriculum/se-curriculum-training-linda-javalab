# Linda First Java Lab 

## Learning Goals

- Learning Goal 1
- Learning Goal 2

## Introduction

A 1-2 sentence summary of what will be covered.

## Instructions

Walk the student through any setup required to run the lesson (i.e.
`npm install` and `npm start`).

## Testing table with code


The `Function<T, R>` interface in the `java.util.function` package accepts a
value of type `T` and returns a result of type `R`. We pass in the arguments to
the `apply` method of the interface.

<table>

<tr>
<th>Don't do this</th>
<th>Do this</th>
</tr>

<tr>
<td>
<pre>
<code>
@FunctionalInterface
interface MyStringIntFunction {
  int apply(String s);
}
</code>
</pre>

<pre>
<code>

MyStringIntFunction length = str -> str.length();
System.out.println( length.apply("hello") ); //5
</code>
</pre>
</td>

<td>
<pre>
<code>
import java.util.function.Function;

Function&lt;String,Integer&gt; length = str -> str.length();
System.out.println( length.apply("hello" ) ); //5
</code>
</pre>
</td>
</tr>

</table>


## Deliverables

List each of the deliverables the student must complete in order to finish the
lab. Provide as much context as possible, including instructions on how to run
the tests and other means of validating successful completion of deliverables.

## Conclusion

A short one or two paragraph summary of the contents of the lessons, recapping
the learning goals.

## Resources

- [Resource Link 1](example.com)
- [Resource Link 2](example.com)
