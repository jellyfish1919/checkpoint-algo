Here's a shorter **README** for the `sentence_counter` algorithm:

---

# sentence_counter Algorithm

## Purpose
The `sentence_counter` algorithm counts:
- Characters (excluding the final period)
- Words
- Vowels (both uppercase and lowercase)

## Input & Output
- **Input**: A sentence ending with a period (e.g., `Good morning we are at GMC.`).
- **Output**:
  - Number of characters
  - Number of words
  - Number of vowels

## Steps
1. **Prompt Input**: Ask the user for a sentence ending with `.`.
2. **Initialize Counters**: Set `cptChar`, `cptW`, and `cptV` to 0.
3. **Loop Through Characters**:
   - Count each character (`cptChar++`).
   - If the character is a space, increment word count (`cptW++`).
   - If the character is a vowel, increment vowel count (`cptV++`).
4. **End Loop** at the period (`.`).
5. **Adjust Counts**: Add 1 to `cptChar` (for the period) and to `cptW` (for the last word).
6. **Display Results**: Print `cptChar`, `cptW`, and `cptV`.

## Example
For `Good morning we are at GMC.`:
- **Characters**: 24
- **Words**: 6
- **Vowels**: 9

--- 

This summary covers the main points concisely.
*****************************************************************************************
Here’s a concise **README** for the `Insertion_Sort` algorithm:

---

# Insertion_Sort Algorithm

## Purpose
The `Insertion_Sort` algorithm sorts a list of integers in ascending order.

## Input & Output
- **Input**: 
  - `n`: The number of elements in the list.
  - `Tab`: An array of `n` integers provided by the user.
- **Output**: The sorted list of integers.

## Steps
1. **Input Array**:
   - Prompt the user for the number of elements (`n`).
   - Read each element of the list into the array `Tab`.
   
2. **Sorting**:
   - For each element from the second to the last (`i = 1` to `n - 1`):
     - Set `key` to the current element (`Tab[i]`).
     - Compare `key` with elements before it, shifting elements greater than `key` to the right.
     - Insert `key` at the correct position in the sorted part of the array.

3. **Output Sorted Array**:
   - Display the sorted list of integers.

## Example
For an input list `[5, 2, 9, 1, 5, 6]`, the output would be `[1, 2, 5, 5, 6, 9]`.

---

This README outlines the algorithm's purpose, inputs, outputs, and process in a concise manner.
