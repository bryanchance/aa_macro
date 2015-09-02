# macro() Changelog

1.0.44 - September 1st, 2015
 * added style=styleName to all conditionals

1.0.43
 * removed auto-generation of newlines in [table] and [row]
 * added [vb] escape for |

1.0.42
 * added parms=X and posts=X to [dlist]

1.0.41
 * added [lcopy], [dcopy], [dkeys]

1.0.40
 * added [fref], [resolve]

1.0.39
 * added [date], [time], [sys]

1.0.38
 * added [ifge], [ifle]

1.0.37
 * added [lcc]

1.0.36
 * added [lsub]

1.0.35
 * added [include], [embrace], [lf], [expand]

1.0.34
 * added [lpop], [lpush] (synonym for append)

1.0.33
 * Moved the 'dothis' named parameter to first in class for simplest invocation

1.0.32
 * added [lslice]

1.0.31
 * added [llen]

1.0.30
 * added [hsort], [lhsort]

1.0.29
 * added [strip]

1.0.28
 * added [soundex]

1.0.27
 * added [count]

1.0.26
 * added [lc], [wc]

1.0.25
 * added [dtohex], [dtooct], [dtobin], [htodec], [otodec], [btodec]

1.0.24
 * added [gpage],[ghost]

1.0.23
 * added [max], [min]

1.0.22
 * added [ltol]

1.0.21
 * added [scase]

1.0.20
 * added [ssort], [sisort], [issort]

1.0.19
 * added [capw], [caps], [capt], [inter]

1.0.18
 * added (sep=X,) option to [push]

1.0.17
 * added [rjust],[ljust],[center]
 * added sep=X to [list] options
 * added sep=X to [ul] options
 * added sep=X to [ol] options
 * added sep=X to [iful] options
 * added sep=X to [ifol] options

1.0.16
 * added [find],[replace]

1.0.15
 * added [rstrip],[ord],[dup]

1.0.14
 * added [list],[lset],[e],[cmap],[translate],[asort],[aisort],[isort],[dlist],[append]
 * added [splitcount]

1.0.13
 * added [eq] to complement [ne]

1.0.12
 * added [locimg] to generate images with width and height set (jpg,png,gif)
 * added [lipath] to tell [locimg] where image file is in local filesystem

1.0.11
  * added [urlencode]

1.0.10
 * added [nl] for non-newline newline encoding in source (0x0a)
 * [img] now sets alt= as well as title=

1.0.9
 * added [bq] for HTML blockquote

1.0.8
 * added [mode] to control HTML output mode from source
 * added [back] to control HTML 4.01s background text color from source
 * added __str__() method for output of initially passed-in input in dothis

1.0.7
 * enhanced [img]
 * fixed bug in [web]
 * fixed bug in parser. Regex, sigh. Live by it, die by it.
 * if you end a line with two trailing spaces, object.do()
will "eat" them, and the following newline, unles you
set nodinner=True

1.0.6
 * added sanitize() utility to help make user input safer
 * sped up [roman numberString] when fed zero
 * added home page to class header
 * added polcies to class header
 * updated class documentation

1.0.5
 * added warning about parsing user input
 * wrote a walkthrough for generating roman numerals, consequently I...
 * added [upper textString]
 * added [lower textString]
 * added [roman numberString]

1.0.4
 * added advice on how to use examples

1.0.3
 * spiffied up the class docs a little
 * added [split splitSpec,contentToSplit]
 * added [parm N]
 * added to examples

1.0.2
 * added new URL link mechanism [a (tab,)URL(,LinkedText)]
[link] and [web] will remain as per my "I will never
take away something you may have used" policy, but
[a] is really a better way to go about it now.
 * added escape for all commas [nc TextToBeEscaped]
 * added non-rendering [comment content] capability
 * added [slice sliceSpec,contentToSlice] capability

1.0.1
 * added HTML paragraphs as [p paragraph]

1.0.0
 * Initial Release