# LongestCharacterInString
```js
// Test Case 1: Test with Different Words Lengths
  const sentence1 = "Smart people learn from everything and everyone, average people from their experience, stupid people already, have all the answers";
  console.log(getLongestWord(sentence1)); // Expected output: "experience"
  
  // Test Case 2: Multiple Words having Same Length but different Vowel Counts
  const sentence2 = "Apples have seed but banana not";
  console.log(getLongestWord(sentence2)); // Expected output: "banana"
  
  // Test Case 3: Empty Input
  const sentence3 = "";
  console.log(getLongestWord(sentence3)); // Expected output: ""
  
  // Test Case 4: Input with No Vowels
  const sentence4 = "This is Gypsy!";
  console.log(getLongestWord(sentence4)); // Expected output: "Gypsy"
  
  // Test Case 5: Input with Special Characters
  const sentence5 = "I like Mangoes, but it was $5.";
  console.log(getLongestWord(sentence5)); // Expected output: "Mangoes"
  
  // Test Case 6: Input with Multiple Spaces
  const sentence6 = "Very  long    spaces .";
  console.log(getLongestWord(sentence6)); // Expected output: "spaces"
  
  // Test Case 7: Input with Only One Word
  const sentence7 = "Hello";
  console.log(getLongestWord(sentence7)); // Expected output: "Hello"
  
  // Test Case 8: Input with All Lowercase Words
  const sentence8 = "all lowercase words in sentence";
  console.log(getLongestWord(sentence8)); // Expected output: "lowercase"
  
  // Test Case 9: Input with All Uppercase Words
  const sentence9 = "ALL UPPERCASE WORDS IN SENTENCE";
  console.log(getLongestWord(sentence9)); // Expected output: "UPPERCASE"
  
  // Test Case 10: Input with Mixed Case Words
  const sentence10 = "Mixed CaSe";
  console.log(getLongestWord(sentence10)); // Expected output: "Mixed"
```
