# Results

## Validation Set

The lyrics: _"my baby don't care"_

Ground Truth:<br>
<audio controls>
    <source src="validation_gt.mp3" type="audio/mp3">
</audio><br>
```
['SOS', 'D4_S', 'D4', 'BREAK', 'D4_S', 'D4', 'C#4_S', 'C#4', 'BREAK', 'C#4_S', 'C#4', 'C#4', 'C#4', 'C#4', 'BREAK', 'B3_S', 'B3', 'B3', 'B3', 'BREAK', 'EOS', 'EOS', 'EOS', 'EOS']
```

Prediction:
```
['SOS', 'G4_S', 'A4', 'BREAK', 'C5_S', 'C5', 'C5_S', 'D5', 'BREAK', 'A4_S', 'A4', 'A4', 'A4', 'A4', 'BREAK', 'G4_S', 'A4', 'G4', 'G4', 'BREAK', 'EOS', 'EOS', 'EOS', 'EOS']
```

First Note Smoothing:<br>
<audio controls>
    <source src="validation_first_note.mp3" type="audio/mp3">
</audio><br>
Majority Note Smoothing:<br>
<audio controls>
    <source src="validation_majority_note.mp3" type="audio/mp3">
</audio>

## Test Set

The lyrics: _"you're creating a"_

Ground Truth:<br>
<audio controls>
    <source src="test_gt.mp3" type="audio/mp3">
</audio><br>
```
['SOS', 'F4_S', 'F4', 'F4', 'F4', 'F4', 'F4', 'BREAK', 'G4_S', 'G4', 'G4', 'G4', 'G4_S', 'G4', 'G4', 'G4', 'BREAK', 'F4_S', 'BREAK', 'EOS', 'EOS', 'EOS', 'EOS', 'EOS']
```

Prediction:
```
['SOS', 'A4_S', 'A4', 'A4', 'C5', 'C5', 'C5', 'BREAK', 'C5_S', 'C5', 'D5', 'F#5', 'D5_S', 'D5', 'C5', 'C5', 'BREAK', 'C5_S', 'BREAK', 'EOS', 'EOS', 'EOS', 'EOS', 'EOS']
```
First Note Smoothing:<br>
<audio controls>
    <source src="test_first_note.mp3" type="audio/mp3">
</audio><br>
Majority Note Smoothing:<br>
<audio controls>
    <source src="test_majority_note.mp3" type="audio/mp3">
</audio>

## Real Songs

### Bohemian Rhapsody - Queen:
_"mama just killed a man put a gun against his head pulled my trigger now he's dead"_

Prediction:
```
['SOS', 'D#4_S', 'D#4', 'E5_S', 'E5', 'E5', 'BREAK', 'D#5_S', 'C5', 'C5_S', 'C5', 'C5', 'BREAK', 'C5_S', 'C5', 'D#5_S', 'C5', 'C5', 'BREAK', 'F4_S', 'F4', 'F4', 'F4', 'BREAK', 'C5_S', 'C5', 'BREAK', 'D#5_S', 'F5', 'F5', 'F5_S', 'F5', 'BREAK', 'F4_S', 'F4', 'BREAK', 'F5_S', 'F5', 'F5', 'BREAK', 'F5_S', 'F5', 'F4', 'F4', 'BREAK', 'G4_S', 'G4', 'F#4', 'F#4', 'F#4', 'BREAK', 'A4_S', 'G4', 'F#4', 'F#4', 'F#4', 'EOS']
```

First Note Smoothing:<br>
<audio controls>
    <source src="bohemian_rhapsody_first_note.mp3" type="audio/mp3">
</audio><br>
Majority Note Smoothing:<br>
<audio controls>
    <source src="bohemian_rhapsody_majority_note.mp3" type="audio/mp3">
</audio>

### Skater Boi - Avril Lavigne

Lyrics: _"he was a boy she was a girl can i make it any more obvious"_


Prediction:
```
['SOS', 'B4_S', 'B4', 'BREAK', 'A#5_S', 'A#5', 'B4', 'BREAK', 'E5_S', 'BREAK', 'A#5_S', 'C#4', 'A#5', 'BREAK', 'A#3_S', 'A#3', 'A#3', 'BREAK', 'D#4_S', 'F4', 'D4', 'BREAK', 'D4_S', 'BREAK', 'D#4_S', 'D4', 'D4', 'D4', 'BREAK', 'B4_S', 'D4', 'D4', 'BREAK', 'E4_S', 'BREAK', 'A#5_S', 'A#5', 'A#5', 'E4', 'BREAK', 'E4_S', 'D4', 'BREAK', 'D4_S', 'D4_S', 'D4', 'BREAK', 'D4_S', 'D4', 'D4', 'D4', 'BREAK', 'D4_S', 'BREAK', 'A5_S', 'A5', 'A5', 'A5', 'A5', 'EOS']
```

First Note Smoothing:<br>
<audio controls>
    <source src="skater_boi_first_note.mp3" type="audio/mp3">
</audio><br>
Majority Note Smoothing:<br>
<audio controls>
    <source src="skater_boi_majority_note.mp3" type="audio/mp3">
</audio>

### Money Money Money - Abba

Lyrics: _"money money money must be funny in the rich man's world"_

Prediction:
```
['SOS', 'D#4_S', 'D#4', 'E5_S', 'E5', 'E5', 'BREAK', 'D#5_S', 'C5', 'C5_S', 'C5', 'C5', 'BREAK', 'C5_S', 'C5', 'D#5_S', 'C5', 'C5', 'BREAK', 'F4_S', 'F4', 'F4', 'F4', 'BREAK', 'C5_S', 'C5', 'BREAK', 'D#5_S', 'F5', 'F5', 'F5_S', 'F5', 'BREAK', 'F4_S', 'F4', 'BREAK', 'F5_S', 'F5', 'F5', 'BREAK', 'F5_S', 'F5', 'F4', 'F4', 'BREAK', 'G4_S', 'G4', 'F#4', 'F#4', 'F#4', 'BREAK', 'A4_S', 'G4', 'F#4', 'F#4', 'F#4', 'EOS']
```

First Note Smoothing:<br>
<audio controls>
    <source src="money_first_note.mp3" type="audio/mp3">
</audio><br>
Majority Note Smoothing:<br>
<audio controls>
    <source src="money_rhapsody_majority_note.mp3" type="audio/mp3">
</audio>

### Hallelujah - Leonard Cohen

Lyrics: _"i'd heard there was a secret chord that david played and it pleased the lord but you don't really care for music do you"

Prediction:
```
['SOS', 'E5_S', 'E5', 'E5', 'BREAK', 'E5_S', 'E5', 'E5', 'E5', 'E5', 'BREAK', 'D5_S', 'D5', 'D5', 'E5', 'E5', 'BREAK', 'D5_S', 'D5', 'B4', 'BREAK', 'D5_S', 'BREAK', 'E5_S', 'E5', 'E5_S', 'E5', 'E5', 'E5_S', 'BREAK', 'E5_S', 'E5', 'E5', 'E5', 'E5_S', 'BREAK', 'E5_S', 'E5', 'A3', 'E5', 'BREAK', 'E5_S', 'E5', 'E5_S', 'E5', 'E5', 'BREAK', 'D4_S', 'D4', 'D4_S', 'A#3_S', 'A#3', 'G#3', 'BREAK', 'D4_S', 'G#3', 'G#3', 'BREAK', 'E5_S', 'G#3', 'BREAK', 'G#3_S', 'E5_S', 'E5', 'E5', 'E5', 'E5', 'E5', 'BREAK', 'E5_S', 'E5', 'E5', 'BREAK', 'E5_S', 'C4', 'C4_S', 'D4', 'BREAK', 'E5_S', 'C4', 'C4', 'BREAK', 'C4_S', 'C4', 'C4', 'BREAK', 'C4_S', 'C4', 'C4', 'F#4', 'F#4', 'BREAK', 'F#4_S', 'F#4', 'F#4', 'F#4', 'F#4', 'F#4', 'BREAK', 'F#4_S', 'F#4', 'F4', 'F#4', 'BREAK', 'C4_S', 'F#4', 'C4', 'BREAK', 'C4_S', 'C4', 'C4_S', 'C4', 'C4', 'BREAK', 'C4_S', 'C4', 'BREAK', 'C4_S', 'D4', 'C4', 'EOS']
```

First Note Smoothing:<br>
<audio controls>
    <source src="hallelujah_first_note.mp3" type="audio/mp3">
</audio><br>
Majority Note Smoothing:<br>
<audio controls>
    <source src="hallelujah_majority_note.mp3" type="audio/mp3">
</audio>