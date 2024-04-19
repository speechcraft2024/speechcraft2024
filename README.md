
# Dataset Observation
SpeechCraft is a large-scale expressive bilingual speech dataset with natural language descriptions resulting from an automatic speech annotation system.
It encompasses over 2,000,000 audio clips annotated with two versions of text prompts, called speech Descriptions (exclude transcript) and speech Instructions (include transcript).

We are planning to open source SpeechCraft, making it the laregest natural language stylistic dataset that encompass the most fine-grained attributes and the most diverse natural language descriptions available.


# Experimental Results
## Experimental Results for Expressive Speech Synthesis

| Style Prompt | Text | Audio (TextrolSpeech Demo) | Audio (SpeechCraft Description Version) |
|:-------------|:-------------|:------------------|:------------------|
<!-- | The despair woman's high-pitched voice carried a slow speech. | A doctor believes this boy to be mad. | <audio controls><source src="./userstudy/5/1_decompressed.wav" type="audio/mpeg"></audio> | <audio controls><source src="./userstudy/5/infer-vocos-0100.wav" type="audio/mpeg"></audio> |
| The despair woman's high-pitched voice carried a slow yet energetic speech. | Racism has no place in any sport. | <audio controls><source src="./userstudy/5/2_decompressed.wav" type="audio/mpeg"></audio> | <audio controls><source src="./userstudy/5/infer-vocos-0101.wav" type="audio/mpeg"></audio> |
| Rapidly speaking, the despair man's deep voice resonates with a sense of normal energy. | A doctor believes this boy to be mad. | <audio controls><source src="./userstudy/5/3_decompressed.wav" type="audio/mpeg"></audio> | <audio controls><source src="./userstudy/5/infer-vocos-0102.wav" type="audio/mpeg"></audio> |
| The despair woman's voice resonated slowly, her miserable energy remaining low, pitch high. | Racism has no place in any sport. | <audio controls><source src="./userstudy/5/4_decompressed.wav" type="audio/mpeg"></audio> | <audio controls><source src="./userstudy/5/infer-vocos-0103.wav" type="audio/mpeg"></audio> |
| A boy said in a desperate voice. | One even gave my little dog a biscuit. | <audio controls><source src="./userstudy/5/5_decompressed.wav" type="audio/mpeg"></audio> | <audio controls><source src="./userstudy/5/infer-vocos-0104.wav" type="audio/mpeg"></audio> |
| The despair woman's voice resonated slowly, her miserable energy remaining low, pitch high. | One even gave my little dog a biscuit. | <audio controls><source src="./userstudy/5/6_decompressed.wav" type="audio/mpeg"></audio> | <audio controls><source src="./userstudy/5/infer-vocos-0105.wav" type="audio/mpeg"></audio> | -->


## Experimental Results for Fine-Grained Speech Emphasis Control

| Style Prompt | Word Emphasis | Audio (Description Version) | Audio (Instruction Version) |
|:-------------|:------------- |:------------------|:------------------|
<!-- | Speaking with a natural tone and at a normal speed, a young girl with normal pitch and low volume says, "'It is a story,' Sara would answer.", adding a touch of charm to the conversation, highlighting "story" with pronounced emphasis. |story| <audio controls><source src="./userstudy/1/infer-vocos-0417.wav" type="audio/mpeg"></audio> | <audio controls><source src="./0417.wav" type="audio/mpeg"></audio> |
| In an environment where naturalness rules, a calm adult male with normal pitch and low volume speaks rapidly, expressing: "That was something over thirteen years ago.", projecting "years" with significant stress. |years| <audio controls><source src="./userstudy/1/infer-vocos-0429.wav" type="audio/mpeg"></audio> | <audio controls><source src="./userstudy/1/0429.wav" type="audio/mpeg"></audio> |
| A youthful male with normal pitch and low volume explosively states, "Here I can cheaply purchase a delicious self-approval." He speaks rapidly in a natural manner, drawing attention to "self" by stressing it significantly. |self| <audio controls><source src="./userstudy/1/infer-vocos-0440.wav" type="audio/mpeg"></audio> |  <audio controls><source src="./userstudy/1/0440.wav" type="audio/mpeg"></audio> |
| A fast-paced conversation with a youth female with low pitch and low volume: "Were you born in Spain, Pablo?", uttering "Spain" with particular stress. |Spain| <audio controls><source src="./userstudy/1/infer-vocos-0502.wav" type="audio/mpeg"></audio> | <audio controls><source src="./userstudy/1/0502.wav" type="audio/mpeg"></audio> | -->

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
