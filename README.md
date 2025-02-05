Calculates the distance between two user input words based on their phonetic features.
1. Word is first parsed into syllables, which are parsed into codas and onsets.
2. Each coda and onset within each syllable is broken down into its IPA components
3. Each IPA component is converted into IPA features (e.g., for consonants, manner/place of articulation and voice). Features have been assigned a penalty for total number of differences.
4. Levenstein distance is used to compare strings of features.

5. Note: this is early code that could be heavily condensed, which I created prior to knowing how to use of functions.
