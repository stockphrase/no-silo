---
title: Search with Precision
bookHidden: true
bookFlatSection: false
bookToc: true
type: docs
---

<div style="text-align:center">{{< figure src="/img/workshop3.png" width=150 >}}</div>


## Searching with Precision

This workshop is designed to help you search library catalogs and other databases with efficiency. While most students have some familiarity with searching through the Google search engine, library catalogs and databases don't always work in the same way. To query databases effectively and efficiently, you need to be familiar with `Boolean` searches.

Perhaps the common research problem is searches that produce too many results. Rather than page through hundreds or thousands of search results, you can use Boolean search strings to make your searches more precise. Boolean searches use what are known as ``logical operators`` to form search strings. 

The three most common logical operators are **AND**, **OR**, and **NOT**. However, you should also learn how to use `exact phrases`, `truncation`, and `wildcards` in search strings. 

- #### <i class="fas fa-volume-up"></i> [**Lecture 4: Searching with Precision**](https://drive.google.com/file/d/1WlJV5O2YSOC7VQGHCG1N-aM7kXRqrVVi/view?usp=sharing)

## Workshop

Study the following information, then complete the problem sets.

#

| Operator   | Purpose | Example    
|:----------|:-------------|---------|
| `AND` | Narrow a search by adding additional keywords | Tom Hardy AND shirtless
| `OR` | Broaden a search by adding additional keywords | Ohio OR Virginia
| `NOT` | Prune search results by removing certain keywords | Vikings NOT football
| `"..."` | Return results containing an exact phrase | "artificial intelligence"
| `*`     | Truncation: used to capture all the word endings from a search term    | manufact*
| `?`     | Wildcard: Finds spelling variations   | organi?ation, wom?n

### Boolean search examples

These Boolean terms are described in more detail below:

{{< details "AND" closed >}} 

#

Although it may seem counterintuitive, `AND` is used to *narrow* the
number of sources you retrieve from a database. You can visualize the
search of a large academic database or library catalog using the
following diagram:

<div style="text-align:center">{{< figure src="/img/and.png" >}}

{ linguistics `AND` cognitive `AND` childhood }</div>

In the search depicted above, a student has requested articles that
contain the subjects **cognitive**, **linguistics**, and **childhood**.
This particular search will only retrieve articles that contain *all
three terms*. This small subset of the larger subject sets is referenced
by the arrow. All the information represented by the other portions of
the three circles will be excluded. Thus, even if an article contains
two of the three search terms, it will be excluded from the results.

{{< hint info >}}

This search could have been improved with `truncation`, described below.

{{< /hint >}}

{{< /details >}}

{{< details "OR" closed >}} 

#

Unlike the `AND` operator, `OR` seeks to *broaden* a search, as in
this example:

<div style="text-align:center">{{< figure src="/img/or.png" >}}


{ Virginia `OR` Ohio }</div>

In the search depicted above, a student has searched for the subjects
Virginia `OR` Ohio. This search will return *every* article having the
subject of Virginia as well as *every* article with the subject of Ohio.
Unlike the `AND` search, where only articles containing *both* terms
are returned in the search results, the `OR` search yields every
source on both subjects regardless of whether those subjects appear
together in the same source. As a consequence, the `OR` search will
produce far more results.

-   Since the `OR` operator lacks precision, it is most often used in
    parenthetical searches, described below.

{{< /details >}} 

{{< details "NOT" closed >}} 

#

The Boolean operator `NOT` is used to *subtract* or *screen out*
topics or keywords that are unwanted within the search results.

<div style="text-align:center">{{< figure src="/img/not.png" >}}


{ "alternative energy" `NOT` solar }</div>

In the search depicted above, a student is researching alternative
energy and wants to exclude any information dealing with solar energy.
To remove all references to solar energy, the student has searched for
"**alternative energy**," but has removed any articles from the search
results that contain the subject **solar** using the operator `NOT`.

The `NOT` operator is helpful when you find your search results are
polluted with unwanted items. This is often a problem when two
distinct things share the same name. For example, if you were
researching the Norse explorers known as the Vikings, you might discover
that your search results include unwanted information about the
Minnesota Vikings football team. You can subtract these unwanted results
by searching for **Vikings `NOT` Minnesota** or **Vikings `NOT` football**,
for example.

{{< hint info >}}

This search uses quotation marks to form an `exact phrase` search, described below.

{{< /hint >}}


{{< /details >}} 

### Advanced searching

These Boolean operators can be used to create long, increasingly precise search strings when they are fortified with more advanced operators: `parentheticals`, `exact phrases`, and `wildcards`.

{{< details "Parenthetical searches" closed >}} 

You can also use the various Boolean search terms in tandem using
parenthetical constructions:

-   (Ohio OR Virginia) AND unemployment

-   (cognitive AND linguistics) NOT childhood

Such parenthetical searches follow the [order of operations](https://en.wikipedia.org/wiki/Order_of_operations), like in math
equations. In the first example, the search will first combine all the
articles with the keyword of **Ohio** to all the articles with the keyword **Virginia**, creating a large collection of search results. Afterward, the keyword **unemployment** will be applied to that collection using the `AND` operator, yielding the final search results that look for sources dealing with unemployment in either Virginia and Ohio. Similarly, the second example creates a large collection of results that share the subjects **cognitive** and **linguistics**, then all the items having the term **childhood** are removed from the results.

{{< /details >}} 


{{< details "Exact phrase searches" closed >}} 

#

Most Internet search engines and library catalogs default to the `AND`
operator when multiple terms are entered, even if it has not been typed
by the user. For example, if you search for **artificial intelligence**,
the search algorithm will actually use the search string **artificial
`AND` intelligence** to produce your results. In some circumstances this
may produce undesirable results. For example, we might
imagine an article about the "intelligence" of using certain
"artificial" sweeteners in food for children. This is not an article that is relevant for your project.

To avoid this problem, you can instruct your search engine to perform
what is known as an `exact phrase search`. This is performed by
placing quotation marks around the exact words you are searching for:

- "artificial intelligence" AND apocalypse 

By searching for "artificial intelligence" your search results will only
contain items that have that exact phrase within the document or title.


{{< /details >}} 

{{< details "Truncation and wildcards" closed >}} 

#

-   manufact\* (truncation)

-   wom?n (wild card)

If you search for the terms steel `AND` manufacturing, your search
results may not include results with the terms **manufacturer**,
**manufacture**, **manufactured**, or **manufactures**. As a result, you
may not discover articles or books that are important to your research.
By truncating the word with an asterisk, however, you will gather all the
relevant search results.

Similarly, if you only search for wom**an**, you will potentially miss out on
the all the texts that mention wom**en** or wom**y**n. Or imagine that you are doing research on a certain type of organization. It would be wise to search for **organi?ation**, since much of the English-speaking world spells the word with an "s" instead of a "z" as we do here in the US. Without this, your research may become skewed to favor the literature on US-based institutions. However, using the wild card `?` you will search all spellings simultaneously, gathering all the
relevant results. *The question mark wild card should be used to replace a single letter only*.

 

 To illustrate, look at these two searches on the JSTOR database:

- [Iraq and manufacturing](https://www-jstor-org.dartmouth.idm.oclc.org/action/doAdvancedSearch?q0=Iraq+and+manufacturing&f0=all&c1=AND&q1=&f1=all&c2=AND&q2=&f2=all&c3=AND&q3=&f3=all&c4=AND&q4=&f4=all&c5=AND&q5=&f5=all&c6=AND&q6=&f6=all&acc=on&la=&sd=&ed=&pt=&isbn=&group=none) (14,863 results)

- [Iraq and manufact*](https://www-jstor-org.dartmouth.idm.oclc.org/action/doAdvancedSearch?q0=Iraq+and+manufacturing&f0=all&c1=AND&q1=&f1=all&c2=AND&q2=&f2=all&c3=AND&q3=&f3=all&c4=AND&q4=&f4=all&c5=AND&q5=&f5=all&c6=AND&q6=&f6=all&acc=on&la=&sd=&ed=&pt=&isbn=&group=none) (30,868 results) 👀️

{{< /details >}} 


## Problem Sets

1. You are interested in investigating *fictional portrayals* of Arab-Israeli conflict. Create a Boolean search string to search the library catalog with.
2. 





<!---
1. Israel* AND (Arab* OR Palestin*) AND (literature OR fiction) 
--->


