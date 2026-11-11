# Tango Sprint 単語

A fast Japanese vocabulary trainer: the 3,000 most frequent everyday Japanese words, each with kana, romaji, meaning, spoken audio (your device's Japanese text-to-speech) and real example sentences.

- Words unlock in frequency order (start with the top 500, add more whenever you like).
- Example sentences are chosen from ones built mostly from words you've already learned.
- Spaced-repetition reviews, quick quizzes (meaning / reverse / listening), streak and daily goal.
- Progress is stored in your browser (localStorage).

Static site: `index.html` + `data.json`. No build step.

## Data and licenses

- Word ranking and example sentences: [Tanaka Corpus](http://www.edrdg.org/wiki/index.php/Tanaka_Corpus), cleaned version [marmooo/tanaka-corpus-plus](https://github.com/marmooo/tanaka-corpus-plus), CC BY 4.0.
- Meanings and readings: [JMdict](https://www.edrdg.org/jmdict/j_jmdict.html) © the Electronic Dictionary Research and Development Group, CC BY-SA 4.0.
- Sentence kana readings are machine-generated (MeCab/UniDic) and may contain errors.

Because `data.json` includes JMdict-derived content, it is shared under CC BY-SA 4.0.
