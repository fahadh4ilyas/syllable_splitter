## Indonesian Syllable Splitter

This is python script for split indonesian word into its syllable.
This script can also split sentences into syllable token.

```python
from SyllableSplitter import SyllableSplitter

ss = SyllableSplitter()

ss.split_syllables("aku dan kamu ekstra hari jum'at")
#['a', 'ku', ' ', 'dan', ' ', 'ka', 'mu', ' ', 'eks', 'tra', ' ', 'ha', 'ri', 'jum', "'", 'at']
```

### CAUTION!

It would be better if you split long sentence into a couple of sentences.
It would reduce the computation time.