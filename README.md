# indonesian_words
 
A package containing the most ~5000 used Indonesian words and some utility
functions.

## Usage

Printing the top 50 most used nouns in the Indonesian language:

    import 'package:indonesian_words/indonesian_words.dart';

    main() {
      nouns.take(50).forEach(print);
    }

Computing number of syllables in a word:

    syllables('beautiful');  // 3
    syllables('abatement');  // 3
    syllables('zoology');  // 4

Generating 5 interesting 2-syllable word combinations:

    generateWordPairs().take(5).forEach(print);
 
