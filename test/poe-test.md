<style type="text/css">
.res {
	color: red;
	font-weight: bold;
}
.act {
	color: green;
	font-weight: bold;
}
</style>


![W3C Logo](https://www.w3.org/Icons/w3c_home)
# Meeting: Permissions and Obligations Expression Working Group Teleconference
**Date:** 20 February 2017

See also the [Agenda]($headers.agenda) and the [IRC Log](poe-test.txt)
## Attendees
**Present:** renato, victor, michaelS, sabrina, benws_

**Regrets:** philA

**Guests:**

**Chair:** Ben

**Scribe(s):** michaelS, michaelS
## Content:
* [1. last week's minutes](#section1)
* [2. deliverables](#section2)
    * [2.1. deliverables - Information Model](#section3)
    * [2.2. deliverables - Vocabulary Document](#section4)
    * [2.3. deliverables - Use Case & Requirements](#section5)
* [3. Other business - actions](#section6)
* [4. London face-to-face](#section7)
* [5. Resolutions](#res)

---


> *victor*: Hi all!

### [1. last week's minutes](id:section1)

**benws_:** minutes are approved


> *renato*: http://w3c.github.io/poe/model/

### [2. deliverables](id:section2)

#### [2.1. deliverables - Information Model](id:section3)

**benws_:** this is a technical document - it starts talking about things which are not relevant for the model, e.g. policy conflicts
 hard to understand and read. How could we order the document better, put important things at the top second issue: policy conflict. unstand what it aims at. But the examples shown there don't raise a conflict by his view.

**renato:** the reason for the conflict is: "use" is a wider term than "print"


**benws_:** what about a policy with "use" and a high payment and a "print" action only and a cheap payment?


**renato:** this example shows a conflict between permission and prohibition in the policies contradicting each other.
 it is about what takes precedence: permission or prohibition

**ivan:** refered to what benws_ said: wouldn't it be better to call this "precedence" than "conflict" ?


> *renato*: https://github.com/w3c/poe/issues/76

**renato:** (searching the POE issue list on Github) this was covered by issue 76
 the "conflict" is in fact more about a strategy to solve conflicting things.

**ivan:** explained formalities: this action is issuing an updated version of an existing document


*(renato)* **Proposed resolution: Publish new working draft of "ODRL Information Model" https://w3c.github.io/poe/model/**

> *ivan*: +1

> *renato*: +1

> *benws_*: +1

> *Sabrina*: +1

> *simonstey*: 0

> *victor*: +1

**simonstey:** explained his abstaining: there are still some open issue, e.g. regarding unclear relations


**renato:** the Information Model is based on UML, not on OWL


**renato:** and simonstey discussed some details - agreed this needs further review


**ivan:** supported the view "this is not the final draft", things may still be modified.


> *renato*: Last published on 21 July 2016

**ivan:** shares simonstey view that XML is only an implementation of the Information Model and not driving it.


**benws_:** who is using ODRL with which format?


**renato:** AP uses XML and also Thomson Reuters, David Compton said XML is used


> *simonstey*: https://www.w3.org/2016/04/25-poe-minutes

**benws_:** would be in favour of an RDF-based canonical specification


> *simonstey*: https://www.w3.org/2016/05/09-poe-minutes

**benws_:** we should look at that again after having published this draft


> *benws_*: +1

**ivan:** saw no problem to have XML implementations and its specific syntax, but this must not drive the information model


**renato:** the Information Model is based on UML and not on XML!!


**ivan:** then the conflict is: UML model vs RDF model. These models cannot be mixed. And UML is not even mentioned anywhere in the Information Model document

<div class="res" id="resolution1">Resolution #1: Publish new working draft of "ODRL Information Model" https://w3c.github.io/poe/model/</div>

#### [2.2. deliverables - Vocabulary Document](id:section4)

> *renato*: https://github.com/w3c/poe/issues/101

**renato:** a few small updates were done - but some issues are still open, e.g. 101
 the ontology was improved.

**benws_:** discussion about normative vs non-normative
 phila had proposed to have only a few normative terms

> *ivan*: +1 to Ben

**benws_:** in the current version of the document we have no explicit "normative" terms and many non-normative terms


**renato:** agreed to apply this change in a future version


**benws_:** what are the criteria for making something normative


**renato:** based on statistics from usages of ODRL


**ivan:** renato's argument is very pragmatic - does not support it.
 the normative terms should build a scafolding and the non-normative terms may be added

**benws_:** in the Action terms use and transfer should be normative


**renato:** that's another way to find the normative terms.


**ivan:** an distinction should be "core" and "additional" terms - this should be based on the information model


*(renato)* **Proposed resolution: Publish new working draft of "ODRL Vocabulary & Expression" https://w3c.github.io/poe/vocab/**

> *ivan*: +1

> *renato*: +1

> *Sabrina*: +1

> *benws_*: +1

> *simonstey*: +1

> *victor*: +1

> [***Resolution #2: Publish new working draft of "ODRL Vocabulary & Expression" https://w3c.github.io/poe/vocab/***](id:resolution2)

> *simonstey*: http://w3c.github.io/poe/ucr/

> *simonstey*: https://www.w3.org/2016/11/07-poe-minutes#resolution02

#### [2.3. deliverables - Use Case & Requirements](id:section5)

**simonstey:** gave an overview: went over UC and checked relationships to Requirements - edited some of them
 requirements which are already covered where "retired" - by strikthrough

**victor:** asked: how long will the Wiki page with use cases exist?


**ivan:** forever - but it will be frozen at the end of the standardisation work


**simonstey:** did some small edits in the UC Wiki doc to fix errors


*(renato)* **Proposed resolution: Publish new working draft of "POE Use Cases and Requirements" https://w3c.github.io/poe/ucr/**

> *simonstey*: +1

> *renato*: +1

> *Sabrina*: +1

> *benws_*: +1

> *ivan*: +1

> *victor*: +1 (again, I have not read it since long, but I rely on future changes to improve possibles areas)

> [***Resolution #3: Publish new working draft of "POE Use Cases and Requirements" https://w3c.github.io/poe/ucr/***](id:resolution3)

**benws_:** three new drafts is a real progress


**renato:** what needs to be done to publish the document ?


**ivan:** the document have to be checked against the W3C publishing rules


> *ivan*: https://www.w3.org/pubrules/

**ivan:** all three drafts should be checked by this rule checking system


> *simonstey*: action-20

### [3. Other business - actions](id:section6)

### [4. London face-to-face](id:section7)

**renato:** the ODRL Community will be invited as observers


**benws_:** Thomson Reuters will host the meeting


---


### [5. Resolutions](id:res)

* [Resolution #1: Publish new working draft of "ODRL Information Model" https://w3c.github.io/poe/model/](#resolution1)
* [Resolution #2: Publish new working draft of "ODRL Vocabulary & Expression" https://w3c.github.io/poe/vocab/](#resolution2)
* [Resolution #3: Publish new working draft of "POE Use Cases and Requirements" https://w3c.github.io/poe/ucr/](#resolution3)
