# Python for Data Analysis
# on Nov 17th 2025 i started learning Data Analysis
<h1 align="center">🐍 Python Basics – Complete Guide</h1>

<p align="center">
  A beginner-friendly explanation of Python fundamentals with examples and visuals.
</p>

<hr>

<h2>📌 Data Types in Python</h2>

<table border="1" cellpadding="8">
  <tr>
    <th>Data Type</th>
    <th>Example</th>
  </tr>
  <tr>
    <td>int</td>
    <td>10</td>
  </tr>
  <tr>
    <td>float</td>
    <td>3.14</td>
  </tr>
  <tr>
    <td>string</td>
    <td>"Hello"</td>
  </tr>
  <tr>
    <td>bool</td>
    <td>True</td>
  </tr>
  <tr>
    <td>list</td>
    <td>[1, 2, 3]</td>
  </tr>
  <tr>
    <td>tuple</td>
    <td>(1, 2, 3)</td>
  </tr>
  <tr>
    <td>set</td>
    <td>{1, 2, 3}</td>
  </tr>
  <tr>
    <td>dictionary</td>
    <td>{"a": 1}</td>
  </tr>
</table>

<pre><code>
x = 10
y = 3.5
name = "Python"
is_active = True
</code></pre>

<hr>

<h2>🔁 Type Conversions</h2>

<h3>Implicit Conversion</h3>
<pre><code>
a = 10
b = 2.5
c = a + b   # Output: 12.5
</code></pre>

<h3>Explicit Conversion</h3>
<pre><code>
int(3.8)       # 3
float(5)       # 5.0
str(100)       # "100"
list("abc")    # ['a', 'b', 'c']
</code></pre>

<hr>

<h2>➕ Operators</h2>

<h3>Arithmetic Operators</h3>
<pre><code>
a = 10
b = 3

a + b   # 13
a - b   # 7
a * b   # 30
a / b   # 3.33
a % b   # 1
a ** b  # 1000
a // b  # 3
</code></pre>

<h3>Logical Operators</h3>
<pre><code>
True and False
True or False
not True
</code></pre>

<hr>

<h2>🔤 Strings</h2>

<pre><code>
s = "Python"

s.upper()   # PYTHON
s.lower()   # python
s[0]        # P
s[1:4]      # yth
len(s)      # 6
</code></pre>

<p><b>String Indexing</b></p>
<pre>
 P   y   t   h   o   n
 0   1   2   3   4   5
</pre>

<hr>

<h2>📋 Lists</h2>

<pre><code>
lst = [10, 20, 30]
lst.append(40)
lst.insert(1, 15)
lst.remove(20)
lst.pop()
</code></pre>

<hr>

<h2>📦 Tuples</h2>

<pre><code>
t = (1, 2, 3)
# t[0] = 10 ❌ Error (Immutable)
</code></pre>

<hr>

<h2>🔢 Sets</h2>

<pre><code>
s = {1, 2, 3, 3}
print(s)   # {1, 2, 3}
</code></pre>

<hr>

<h2>🗂️ Dictionaries</h2>

<pre><code>
student = {
  "name": "Alice",
  "age": 20
}

student["name"]
student.get("age")
</code></pre>

<hr>

<h2>🔁 Loops</h2>

<h3>for Loop</h3>
<pre><code>
for i in range(5):
    print(i)
</code></pre>

<h3>while Loop</h3>
<pre><code>
i = 0
while i < 5:
    print(i)
    i += 1
</code></pre>

<hr>

<h2>⚡ Comprehensions</h2>

<h3>List Comprehension</h3>
<pre><code>
squares = [x**2 for x in range(5)]
</code></pre>

<h3>Set Comprehension</h3>
<pre><code>
unique = {x for x in [1,2,2,3]}
</code></pre>

<h3>Dictionary Comprehension</h3>
<pre><code>
square_dict = {x: x**2 for x in range(5)}
</code></pre>

<hr>

<h2>✅ Summary</h2>

<table border="1" cellpadding="8">
  <tr>
    <th>Data Type</th>
    <th>Mutable</th>
  </tr>
  <tr>
    <td>List</td>
    <td>✅</td>
  </tr>
  <tr>
    <td>Set</td>
    <td>✅</td>
  </tr>
  <tr>
    <td>Dictionary</td>
    <td>✅</td>
  </tr>
  <tr>
    <td>Tuple</td>
    <td>❌</td>
  </tr>
  <tr>
    <td>String</td>
    <td>❌</td>
  </tr>
</table>

<p align="center">
  🚀 <b>Happy Coding!</b>
</p>

