# Array Methods Workshop

## Task 1 - Map

```

let codeCoaches = ['ben', 'chris', 'tim', 'liz', 'mell', 'tao']

```

You have an array of code coaches. Unfortunately, someone forgot to capitalise their names. Declare a new variable, 'capitalisedCodeCoaches', which contains an array with the first letter of all of the code coaches' names capitalised. Use the .map() method to generate the new array.

```

let captialisedCodeCoaches = // Your 'map' code here.

```

## Task 2 - Filter

```

let animals = ['baboon', 'kangaroo', 'rhino', 'frog', 'beaver', 'horse', 'basalisk']

```

You have an array of lovely animals. Unfortunately, you can only keep the animals that start with the letter 'b'. Declare a new variable, 'bListAnimals', which contains only the animals whose name begins with 'b'. Use the .filter() method to generate the new array.

```

let bListAnimals = // Your 'filter' code here.


```

## Task 3 - Some

```

let someNumbers = [4, 5, 6, 78, 2, 3, 45, 34, 2, 23, 5, 45 6, 7, 23]

```

You have an array which contains some numbers. You would like to find out if any of the numbers are multiples of the following numbers:

- 3
- 5
- 60
- 90

Declare four variables, one for each of the above numbers. Use the .some() method to assign a value of true of false to each of the variables, depending on whether there is a multiple of that number in the 'someNumbers' array.

For example:

```

let multipleOf3 = // Your 'some' code here.

```

## Task 4 - Every, Find, Find Index

```

let sevenTimesTable = [7, 14, 21, 28, 35, 42, 49, 56, 63, 70]

let seventySevenTimesTable = [77, 154, 231, 308, 385, 461, 538, 616, 693, 770]

```

You think you know your seven times table, but you're feeling shakey on your seventy seven times table.

- Using the .every() method, check that every number in the 'sevenTimesTable' array is a multiple of 7.

- Check if every number in the seventySevenTimesTable array is a multiple of 77 using the .every() method.

- Your worst fears have been confirmed. There is a rogue value in your 'seventySevenTimesTable' array. Use the .find() method to identify which number it is.

- Now that you know which number is incorrect, use the .findIndex() method to identify the index of the number.

## Task 5 - Nightclub Mutation (Push, Pop, Shift, Unshift, Splice, Concat)

```

let queue = ['catHorse', 'dogPig', 'catHorse', 'dogPig', 'kangarooBear', 'dogPig', 'catHorse', 'catHorse', 'dogPig']

```

You run a nightclub for mutated animals. Naturally, when people join the queue for the nightclub, you mutate the 'queue' array and allow them to wait in line. The queue starts at index 0 (this is the front of the queue).

- Yet another 'catHorse' turns up at the nightclub door. Use an array method to add them to the back of the queue.

- The queue is moving ever slowly forwards, and a mutated animal from the front may enter the nightclub. Remove a mutated animal from the front of the queue using an array method.

- Oh my. An 'owlDonkey' has appeared at the door. Put them straight to the front of the queue using an array method.

- The queue really IS moving very slowly. The 'catHorse' at the back of the queue decides to call it a night. Remove the 'catHorse' at the back of the queue using an array method.

- You have received an emergency phone call concerning the 'kangarooBear' in the middle of the queue. Use an array method to remove the 'kangarooBear' from the middle of the queue.

- Classic. A group of 'rabbitSalmon' have decided to form an unofficial queue next to your queue. Using an array method, merge the unofficial queue into the original queue, so that all of the 'rabbitSalmon' are at the back of the queue.

```

let unofficialQueue = ['rabbitSalmon', 'rabbitSalmon', 'rabbitSalmon', 'rabbitSalmon']

```

## Task 6 - The Immutable Library (Spread and Slice)

You run a library which is filled with immutable books. Some libraries let the public edit the contents of the books however they wish. Well, no such anarchy at your library. It is strictly immutable. You may copy the contents of a book, and edit your own copy, but you may NEVER change the original copy.

```

let bookshelf = [
{title: 'Translations', author: 'Brian Friel'},
{title: 'Inkle and Yarico', author: 'Beryl Gilroy'},
{title: 'Culture and Imperialism', author: 'Edward Said'},
{title: 'Close Range', author: 'Annie Proulx'},
{title: 'Castle Rackrent', author: 'Maria Edgeworth'}
]

```

- Finally, a member of the public arrives! Amazingly, they literally want a copy of every book in your 'bookshelf' array. Using the spread syntax, declare a variable, 'firstBookBag', as an array which contains the entire contents of the 'books' array.

- A more discerning member of the public comes in. They only want a copy of Brian Friel's 'Translations'. Using the slice method, declare a new variable, 'secondBookBag' as an array containing only a copy of 'Translations'.

- Word of the immutable library is spreading. Somebody wants a bag that includes every book except 'Inkle and Yarico'. Using a combination of the spread syntax and the .slice() method, create a new variable, 'thirdBookBag', as an array which includes every book except 'Inkle and Yarico'.

- A person arrives who wants a copy of 'Castle Rackrent'. However, they believe the title should be 'Castle Rackrant'. Clearly incorrect, but since it's their copy they can do as they please. Using only the spread syntax, declare a new variable, 'fourthBookBag', as an array which contains a copy of 'Castle Rackrent', but with the title changed to 'Castle Rackrant'.

## Task 7 - The Sorting Hat (Sort)

You are the sorting hat. Although you're famous for sorting Hogwart's students into houses, it turns out you can sort almost anything.

```

let broomCupboard = [2, 4, 1, 3, 7, 5, 8, 6, 10, 9, 0]

```

- The students always put their broomsticks back in the broom cupboard out of order, despite the fact they are each clearly labeled with a number. No matter, sorting numbers is a piece of cauldron cake. Using the .sort() method, rearrange the brooms (numbers) in the broomCupboard array so that they are in ASCENDING order, with broomstick 1 at index 0 and broomstick 10 and index 9.

```

let potions = [
    {name: 'polyjuice potion', shelf: 2},
    {name: 'draught of living death', shelf: 4},
    {name: 'pepperup potion', shelf: 1},
    {name: 'veritaserum', shelf: 3}
]

```

- Tsk tsk tsk. It looks like Snape can't even sort his own potion cupboard. Using the .sort() method, rearrange the four potions in the 'potions' array so they are in DESCENDING order, with the 'draught of living death' at index 0 and the 'pepperup potion' at index 3.

```

let students = ['Cedric Diggory', 'Padma Patil', 'Lucius Malfoy', 'Seamus Finnigan', 'Lavender Brown', 'Luna Lovegood', 'Gregory Goyle']

```

- Some students have been kept behind in detention by Professor McGonagall. Obsessed with orderliness, she has asked you to sort the students into alphabetical order. Sort the names in the array in alphebetical order according to their last name.
