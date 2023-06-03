AUTOHOTKEY

-duplicate-
function + directive: hotif hotstring
function + function(): goto hotstring msgbox throw
function + keyboard: pause sleep
function + expression/statement: catch else finally if try (excluded: loop until while)

-added-
function(): isalnum isalpha isdigit isfloat isinteger islower isnumber isspace istime isupper isxdigit
variable: super this

-excluded-
keyboard: sc vk

NSIS

-duplicate-
label + variable: pop push

SHELL

-added-
function: back icon import pos separator theme tip title view visibility
function(): item menu
property: index quote
value: after before both bottom disable hidden inherit label maximized middle minimized normal remove show static top visible

-removed-
section: item