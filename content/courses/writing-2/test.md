---
weight: 1
bookFlatSection: true
bookToc: true
bookHidden: true
title: "Test"
---

<script defer src="/static/fontawesome/fontawesome-all.js"></script>


- <i class="fab fa-github"></i>


Outside of the tabs environment, this works as expected:

- {{< fa question-circle  >}} *Question of the Day*: Something you love/hate? 


But inside tabs environment, this breaks the line:

{{< tabs "Week-One" >}}
{{< tab "9.14" >}}

### Course orientation

- Item one
- Item two
- <i class="fab fa-github"></i> This is a test.


{{< /tab >}}

