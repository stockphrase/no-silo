---
weight: 1
bookFlatSection: true
bookToc: true
bookHidden: true
title: "Test"
---

Outside of the tabs environment, this works as expected:

- {{< fa question-circle  >}} *Question of the Day*: Something you love/hate? 


But inside tabs environment, this breaks the line:

{{< tabs "Week-One" >}}
{{< tab "9.14" >}}

### Course orientation

- Item one
- Item two
- {{< fa question-circle  >}} This is a test.


{{< /tab >}}

