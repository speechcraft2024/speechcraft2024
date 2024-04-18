
Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Experimental Results for Fine-Grained Speech Emphasis Control

| Style Prompt | Word Emphasis | Audio (Description Version) | Audio (Instruction Version) |
|:-------------|:------------- |:------------------|:------------------|
| Speaking with a natural tone and at a normal speed, a young girl with normal pitch and low volume says, "'It is a story,' Sara would answer.", adding a touch of charm to the conversation, highlighting "story" with pronounced emphasis. |story| <audio controls><source src="./users study/第一题/infer-vocos-0417.wav" type="audio/mpeg"></audio> | <audio controls><source src="./users study/第一题/0417.wav" type="audio/mpeg"></audio> |
| In an environment where naturalness rules, a calm adult male with normal pitch and low volume speaks rapidly, expressing: "That was something over thirteen years ago.", projecting "years" with significant stress. |years| <audio controls><source src="./users study/第一题/infer-vocos-0429.wav" type="audio/mpeg"></audio> | <audio controls><source src="./users study/第一题/0429.wav" type="audio/mpeg"></audio> |
| A youthful male with normal pitch and low volume explosively states, "Here I can cheaply purchase a delicious self-approval." He speaks rapidly in a natural manner, drawing attention to "self" by stressing it significantly. |self| <audio controls><source src="./users study/第一题/0440.wav" type="audio/mpeg"></audio> |  <audio controls><source src="./users study/第一题/infer-vocos-0440.wav" type="audio/mpeg"></audio> |
| A fast-paced conversation with a youth female with low pitch and low volume: "Were you born in Spain, Pablo?", uttering "Spain" with particular stress. |Spain| <audio controls><source src="./users study/第一题/0502.wav" type="audio/mpeg"></audio> | <audio controls><source src="./users study/第一题/infer-vocos-0502.wav" type="audio/mpeg"></audio> |


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
