# Tuesday 火

A fast Japanese vocabulary trainer built on memory research: the 3,000 most frequent everyday Japanese words, with kana, romaji, meaning, spoken audio (your device's Japanese text-to-speech) and real example sentences.

## How it teaches

- **Recall, don't reread.** New words come in small batches; each is tested a few cards after you first see it and comes back until you recall it (retrieval practice, Karpicke & Roediger, *Science* 2008).
- **Relearn across sessions.** Recalled words return after ~1 h, 8 h, 1 d, 2 d, 4 d… (successive relearning, Rawson & Dunlosky; spacing, Cepeda et al. 2008).
- **Both directions.** Japanese → meaning and meaning → Japanese, plus listening-only recall (transfer between directions is partial: Bernardi, Vaughn & Dunlosky 2024).
- **Most frequent first.** Words are ranked by how often they appear in ~150,000 everyday Japanese sentences.
- **Readable sentences.** Examples are chosen from ones made mostly of words you already know; learned words are marked in blue, and any word can be tapped for its meaning.
- You decide when to unlock more words. Progress is stored in your browser (localStorage).

Static site: `index.html` + `data.json`. No build step.

## Data and licenses

- Word ranking and example sentences: [Tanaka Corpus](http://www.edrdg.org/wiki/index.php/Tanaka_Corpus), cleaned version [marmooo/tanaka-corpus-plus](https://github.com/marmooo/tanaka-corpus-plus), CC BY 4.0.
- Meanings and readings: [JMdict](https://www.edrdg.org/jmdict/j_jmdict.html) © the Electronic Dictionary Research and Development Group, CC BY-SA 4.0.
- Sentence kana readings are machine-generated (MeCab/UniDic) and may contain errors.

Because `data.json` includes JMdict-derived content, it is shared under CC BY-SA 4.0.
