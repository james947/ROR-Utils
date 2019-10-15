Useful Iterators and Methods for Ruby on Rails
===
When you want to travel through the items in a database you created with Ruby on Rails, knowing the iterators to use is key. The following table shows helpful iterators and methods:
---

[1, 2, 3].each { }	=> [1, 2, 3]
[1, nil, nil, 2, 3, nil].compact { }	=> [1, 2, 3]
[1, 2, 3].delete_if { |x| x >= 3 }	=> [1, 2]
[1, 2, 3].collect { |x| x + 1 }	=> [2, 3, 4]
[1, 2, 3].find_all { |x| x % 2 == 1 }	=> [1, 3]
[1, 2, 3].reject { |x| x % 2 == 1 }	=> [2]
[2, 5, 1, 0, 7].sort	=> [0, 1, 2, 5, 7]
[2, 5, 1, 0, 7].max	=> 7
[1, [2, 3]].flatten	=> [1, 2, 3]
[1, 2, 3].empty?	=> false
[].empty?	=> true
[0, 5, 9].length	=> 3
[1, 2, 3].include?(2)	=> true
[1, 2, 3].include?(16)	=> false
[1, 2, 3].reverse	=> [3, 2, 1]