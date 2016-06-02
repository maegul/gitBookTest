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



---

<button class="section" target="section1" show="Show next section" hide="Hide next section"></button>

<button class="section" target="section1" show="Show next section" hide="Hide next section"></button>

<button class="section" target="section1" show="Show next section" hide="Hide next section"></button>

<!--sec data-title="Introduction" data-id="matlab" data-show=true ces-->
```python

def myFunc(a):
  return a**2
  print a
  test =[1, 2, 3]

```
<!--endsec-->

<!--sec data-title="Introduction" data-id="python" data-show=true ces-->
```matlab

test = [];
for i=1:10;
  test = [test i^2];
end;

```
<!--endsec-->

<!--sec data-title="Introduction" data-id="r" data-show=true ces-->
```r

n = c(2, 3, 5) 
s = c("aa", "bb", "cc") 
b = c(TRUE, FALSE, TRUE) 
df = data.frame(n, s, b)

```
<!--endsec-->
