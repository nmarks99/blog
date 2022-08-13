---

layout: "post"

---

<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

## Does code work?

{% highlight rust %}
const y: u32 = 5;

fn main() {
    
  let x:Option<u32> = match y {
    1 => Some(1),
    2 => Some(1),
    3 => Some(123),
    _ => None

}


{% endhighlight %}

