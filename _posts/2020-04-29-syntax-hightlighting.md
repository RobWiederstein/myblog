---
layout: single
title: Syntax Highlighting
date: '2020-04-26 19:53:27 -0500'
excerpt: >-
  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
  incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
  nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
  Duis aute irure dolor in
categories: jekyll update
---

# Syntax Highlighting

```r
a <- 1:10
b <- "a"
l <- list(number = a, names = b)
```

```

a <- 1:10
b <- "a"
l <- list(number = a, names = b)
```

```ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```

{% highlight ruby linenos %} def print_hi(name) puts "Hi, #{name}" end print_hi('Tom')

# => prints 'Hi, Tom' to STDOUT.

{% endhighlight %}

```css
p { color: red }```
