| Feature Name                  | Description |
|-------------------------      |-------------|
| length                        | Length of the request string. |
| special_chars_count           | Number of special characters in the request string. |
| digits_count                  | Number of numeric characters in the request string. |
| entropy                       | Shannon entropy of the request string, measuring randomness. |
| ngram_entropy                 | Entropy calculated based on character n-grams, indicating complexity. |
| diversity                     | Unique character diversity in the request string. |
| num_dots                      | Count of dot ('.') occurrences in the request string. |
| html_tags                     | Presence of HTML tags in the request string. |
| encoded_chars                 | Number of percent-encoded characters (e.g., %20, %3D). |
| num_encoded_chars             | Total count of encoded characters in the request. |
| open_parens                   | Number of opening parentheses '(' in the request string. |
| close_parens                  | Number of closing parentheses ')' in the request string. |
| total_parens                  | Total count of parentheses '(' and ')' combined. |
| unbalanced_parens             | Difference between open and close parentheses, indicating syntax errors or obfuscation. |
| embedding_mean                | Mean value of the embedding vector of the request. |
| medial_scalar                 | Median value of the embedding vector. |
| sum_scalar                    | Sum of all values in the embedding vector. |
| magnitude_scalar              | Magnitude of the embedding vector, representing overall signal strength. |
| digit_to_char_ratio           | Ratio of numeric characters to total characters. |
| special_to_char_ratio         | Ratio of special characters to total characters. |
| dot_to_char_ratio             | Ratio of dot occurrences to total characters. |
| unique_char_ratio             | Ratio of unique characters to total characters. |
| digit_to_special_ratio        | Ratio of numeric characters to special characters. |
| entropy_to_length_ratio       | Ratio of Shannon entropy to the string length. |
| ngram_entropy_to_length_ratio | Ratio of n-gram entropy to the string length. |
| is_malicious_ua               | Binary flag indicating if the user agent is known to be malicious. |
