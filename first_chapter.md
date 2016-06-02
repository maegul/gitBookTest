# First Chapter

{% exercise %}
Make and use a function that takes a number and returns that number as a string with 'px' at the end
{% initial %}
function mkPx(){}
{% solution %}
function mkPx(num){return num+'px';}
{% validation %}
assert(mkPx(10) == '10px');
{% context %}
// This is context code available everywhere
// The user will be able to call magicFunc in his code
function magicFunc() {
    return 3;
}
{% endexercise %}


<!--sec data-title="Introduction" data-id="section0" data-show=true ces-->

Insert markdown content here (you should start with h3 if you use heading).

```python

def myFunc(a):
  return a**2
  print a
  test =[1, 2, 3]

```

more stuff
<!--endsec-->


