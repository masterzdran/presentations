<section data-state="no-title-footer" data-background-image="https://3vnqw32fta3x1ysij926ljs3-wpengine.netdna-ssl.com/wp-content/uploads/2018/05/How-to-Build-a-Campfire.jpg">
<h1>Camp Fire Initiative</h1>
</section>


---
<section data-state="no-title-footer" data-background-image="http://absfreepic.com/absolutely_free_photos/small_photos/puzzle-piece-5184x3888_21238.jpg" data-background-size="80%">
<h1>
Mocking Unit Tests in Netcore</h1>
</section>



---
<section data-state="no-title-footer" data-background-image="https://miro.medium.com/max/530/1*mpofs4MkBpXuRZDpeXCcIA.png" data-background-size="99%">

## Unit Testing
<blockquote cite="http://softwaretestingfundamentals.com/unit-testing/">
... is a level of software testing where individual units/ components of a software are tested. The purpose is to validate that each unit of the software performs as designed. A unit is the smallest testable part of any software.
</blockquote>

---
<section data-state="no-title-footer" data-background-image="http://3.bp.blogspot.com/-E-5fM9X1zKg/TiVfi9vks-I/AAAAAAAAAMc/-XsE9F7U_wo/s1600/ut_common_approach.png" data-background-size="99%">

## What is mocking?
<blockquote cite="https://www.telerik.com/products/mocking/unit-testing.aspx">
... Mocking is a process used in unit testing when the unit being tested has external dependencies. The purpose of mocking is to isolate and focus on the code being tested and not on the behavior or state of external dependencies. In mocking, the dependencies are replaced by closely controlled replacements objects that simulate the behavior of the real ones
</blockquote>
--- 

# Types of replacement objects

--

## Fakes
<blockquote cite="https://www.telerik.com/products/mocking/unit-testing.aspx">
A Fake is an object that will replace the actual code by implementing the same interface but without interacting with other objects. Usually the Fake is hard-coded to return fixed results. To test for different use cases, a lot of Fakes must be introduced. The problem introduced by using Fakes is that when an interface has been modified, all fakes implementing this interface should be modified as well.
</blockquote>

--

## Stubs
<blockquote cite="https://www.telerik.com/products/mocking/unit-testing.aspx">
A Stub is an object that will return a specific result based on a specific set of inputs and usually won’t respond to anything outside of what is programed for the test.
</blockquote>

--

## Mocks
<blockquote cite="https://www.telerik.com/products/mocking/unit-testing.aspx">
A Mock is a much more sophisticated version of a Stub. It will still return values like a Stub, but it can also be programmed with expectations in terms of how many times each method should be called, in which order and with what data.
</blockquote>
---
<section data-state="no-title-footer" data-background-image="https://www.pymnts.com/wp-content/uploads/2015/03/MasterCard-Coding.jpg">
<h2>Let us camp....</h2>

</section>

---
## Resources

* https://martinfowler.com/articles/mocksArentStubs.html
* https://www.telerik.com/products/mocking/unit-testing.aspx