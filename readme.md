<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=dd83f6&height=90&section=header"/>

<img align="right" width="360" src="https://images.ctfassets.net/wfutmusr1t3h/6eWM76bx8skN2B4Jpvkcil/3ccdafea4229f02802abbd9fc6634a3b/Certifiedtocat_full__2_.svg">


  I'm cs major and curious how machine think (and how not to) and besides tech, I love music and F1 !
  
  [mail me ](mailto:mansiruhil99@gmail.com) <br>
  [my portfolio :)](https://mansiruhil.vercel.app/) <br>
  [linkedin ](https://www.linkedin.com/in/mansi-ruhil-7a00a0228/)

  currently working on : <br>
  - data structures & algorithms 
  - machine learning fundamentals
  - agentic AI & LLM reasoning

<br>
<br>
<br>

*my cute lil' hashmap <3 (O(1) always)*

```python
class HashMap:
    def __init__(self):
        self.bucket = []
        for i in range(7):  
            self.bucket.append([])  
        print("hashmap initialized cause built in is too basic")
        # i genuinely love HashMaps <3

    def put(self, key, value):
        index = hash(key) % len(self.bucket)
        for i, (k, v) in enumerate(self.bucket[index]):
            if k == key:
                self.bucket[index][i][1] = value
                print(f" Updated: '{key}' now maps to '{value}'")
                return
        self.bucket[index].append([key, value])
        print(f" Added: '{key}' → '{value}' 'cause i love mapping stuff <3 ")

    def get(self, key):
        index = hash(key) % len(self.bucket)
        for k, v in self.bucket[index]:
            if k == key:
                print(f"Found: '{key}' → '{v}' just like finding answers in life")
                return v
        print(f"Oops: '{key}' not found. doesn’t exist in the map")
        return None

    def remove(self, key):
        index = hash(key) % len(self.bucket)
        before = len(self.bucket[index])
        self.bucket[index] = [pair for pair in self.bucket[index] if pair[0] != key]
        after = len(self.bucket[index])
        if before != after:
            print(f"Removed: '{key}' (if it existed)")
        else:
            print(f"'{key}' wasn’t even here. nothing to remove")

```
<br>
<img src="https://github-readme-stats.vercel.app/api?username=mansiruhil&show_icons=true&layout=compact">
<img src="https://gitroll.io/api/badges/profiles/v1/u9saBZAGw5lbMfbTu7GuYDlfeVgt2" alt="info" /><br /><p align="center"><img src="https://holopin.me/mansiruhil13" alt="cover" /><img loading="lazy" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mansiruhil&langs_count=100&layout=compact&show_icons=true&include_all_commits=true&count_private=true&custom_title=Programming+Langauges&bg_color=ffffff00&title_color=c9d1d9&border_color=262626&text_color=c9c5c5&border_radius=3" width="100%" alt="Top languages" /><br/><br/><img alt="Activity" src="https://github-readme-activity-graph.vercel.app/graph?username=mansiruhil&theme=github-compact" /></p></a><hr />

<br>

<details>
<summary>my stacks:</summary>
<table align="center" class="table table-dark">
  <tr bg-dark>
    <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=html" alt="icon" width="55" height="55" />
      <br>HTML
    </td>
    <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=react" alt="icon" width="55" height="55" />
      <br>React JS
    </td>
    <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=js" alt="icon" width="55" height="55" />
      <br>Javascript
    </td>
    <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=typescript" alt="icon" width="55" height="55" />
      <br>TypeScipt
    </td>
    <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=css" alt="icon" width="55" height="55" />
      <br>CSS
    </td>
  </tr>
  <tr>
    <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=cpp" alt="C++ icon" width="55" height="55" />
      <br>C++
    </td>
    <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=python" alt="icon" width="55" height="55" />
      <br>Python
    </td>
    <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=nextjs" alt="icon" width="55" height="55" />
      <br>Next JS
    </td>
    <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=nodejs" alt="icon" width="55" height="55" />
      <br>Node JS
    </td>
     <td align="center" width="90">
      <img src="https://skillicons.dev/icons?i=git" alt="icon" width="55" height="55" />
      <br>Git
    </td>
  </tr>
</table>
</details>

<br>

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=dd83f6&height=80&section=footer"/>