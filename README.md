# UMAN_data
- The data of UMAN
- Learning Sequential Correlation for User Generated Textual Content Popularity Prediction
- link: xxx

# Detail
- JSON format.
- keys:
  - nb_train, nb_vali, nb_test: number of training/validation/test data
  - train, vali, test: training/validation/test data
    - gpid: post id，increase with time.
    - label: label for prediction, the popularity scroe.
    - user: user id.
    - time: Timestamps.
    - text: word id sequence.
  - nb_words, nb_items, nb_users: number of words/data/users
  - word_dict: mapping of word to word id
  - raw_text: raw text
