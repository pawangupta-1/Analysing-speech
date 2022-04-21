## Forced Alignment of Speech and Transcription

In laymen language, a forced-Alignment is a software package that basically aligns your audio recording to its transcripts at the level of phonemes (such as wa- sh- n- etc.). After the transcription (manual or auto) of audio with time-stamps, at the time of analysis, you will need to analyse specific parts of the audio for specific content that can as be large as sentences spoken over 10 sec to as small as utterances spoken over 10 milliseconds. To extract acoustic prosodic features of specific utterances, your transcription must be aligned to the audio at a very minute level and this is achieved by Forced-Alignment package, referred as FA hereafter.

Majorly an FA is basically a bunch of coding scripts written in a lnagugage such as python that you need to run to do the task. It is not actually a software but simply some lines of codes that need to be run in an IDE or a terminal window of your mac. The FA coding scripts use 4 inputs basically - a transcript; an audio file; an acoustic model; and a pronounciation dictionary. The acoustic model are theoretical models such as HMM (Hidden Markov Model) or DNN (Deep Neural Networks) that set the framework for alignment and are in-built in the FA. The pronounciation dictionary is also an in-built dictionary with a set of vocabulary on which the acoustic model has been trained. You can also provide a new dictionary if your audio file has words outside the existing dictionary of FA you are using. So, basically, you just need to provide the audio and transcription file.

You can use the [editor on GitHub](https://github.com/pawangupta-1/Analysing-speech/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Running the Aligner
So, I installed Montreal Forced Aligner (the instructions for installing it are here _____) and tried running it but received this error

```markdown
Intel MKL FATAL ERROR: This system does not meet the minimum requirements for use of the Intel(R) Math Kernel Library.
The processor must support the Intel(R) Supplemental Streaming SIMD Extensions 3 (Intel(R) SSSE3) instructions.
The processor must support the Intel(R) Streaming SIMD Extensions 4.2 (Intel(R) SSE4.2) instructions.
The processor must support the Intel(R) Advanced Vector Extensions (Intel(R) AVX) instructions.
```

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/pawangupta-1/Analysing-speech/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
