---
layout: essay
type: essay
title: "Don't Ask Dumb Questions"
# All dates must be YYYY-MM-DD format!
date: 2025-01-26
published: true
labels:
  - TypeScript
  - StackOverflow
---
<img width="780px" class="rounded float-start pe-3" src="../img/TYPE.png">

# Dont Ask Dumb Questions

## Introduction
In software engineering, asking the right questions are just as important as finding the right answers. A smart question will display effort, clarity, and detailed respect for the readers time, representing the backbone of effective communication and problem-solving. Eric S. Raymond’s, *How To Ask Questions The Smart Way*, guides readers a method to crafting questions that can lead to significant and efficient solutions. This technical essay explores two opposing examples from Stack Overflow, where there is a smart question and a poorly constructed one. A smart question will meet Raymond's criteria, while the opposite falls short, reflecting on the factors about what makes a question effective.

## A Smart Question: Why is processing a sorted array faster than processing an unsorted array?
*"Why is processing a sorted array faster than processing an unsorted array?"*
[Link](https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array)

A great example of a smart question comes from a Stack Overflow post titled, **"Why is processing a sorted array faster than processing an unsorted array?"** The poster learns there is a performance difference when processing sorted versus unsorted arrays, in C++. Instead of posting a simply stated general question, the poster explained behavioral observations, shared a reproducible code portion, and provided information regarding their system setup, like the compiler and hardware utilized.

Reviewing several of Raymond’s principles, this post aligns with:
1. **Be precise and informative about your problem**:
     A clear and specific description of the issue is provided, including steps with the code that are reproducable.
2. **Describe the goal, not the step**:
   The focus of this post is on the understanding of the reason behind the performance issue, rather than attempting to find a quick fix.
3. **Demonstrate prior research**:
   The system details and code that were included shows that a significant amount of effort was given before asking for help.
4. **Respect the community’s time**:
   This question was structured well, ensuring ease for readers to reply and provide significant answers.

The post responses given were detailed and insightful, with contributors discussing concepts like branch prediction and CPU cache optimization. Due to how this question was posted, this online conversation not only helped the asker but also created a valuable resource for the entire Stack Overflow community. 

## A Poor Question: C# Math.Cos(double) returns wrong value
*"C# Math.Cos(double) returns wrong value."*
[Link](https://stackoverflow.com/questions/11166034/c-sharp-math-cosdouble-returns-wrong-value)

On the flip side, there’s the question: **"C# Math.Cos(double) returns wrong value."** The asker posts, *"In C# I have this: `double Cos = Math.Cos(32.471192290848492); //Equals 0.49299653250335213`. But when I do this in a calculator I get `(0.84366148773210745476752872050588)`. Why is it returning the wrong value?"*.

Reviewing several of Raymond’s principles, this post violates:
1. **Lack of precision and informativeness**:
   This post fails in explaining the discrepancy issues that arise from the use of degrees in the calculator instead of radians in C#.
2. **No evidence of prior research**:
   This question does not indicate that the poster made any attempt to understand the issue before asking, such as reading the documentation for `Math.Cos`.
3. **Failure to describe the goal**:
   Instead of exploring the mechanics of trigonometric functions in programming, this post has a narrow focus upon the unexpected output.
4. **Minimal context**:
   This asker does not explain their environment or the procedures taken to troubleshoot, leaving readers to assume and infer the basics.

The responses made to this post reflect the inefficiency caused by the poorly made question. Many replies specified the distinction between degrees versus radians, providing solutions such as,

```csharp
double angleInDegrees = 32.471192290848492;
double cos = Math.Cos(angleInDegrees * (Math.PI / 180.0));
Console.WriteLine(cos); // Correct value in radians
```

Even though the responses fixed the immediate issue, this question missed the chance to explore deeper into trigonometric functions in programming and their applications. The lack of depth in this question limits its value to the community and its readers. 

## Comparable Lessons
Comparing these two examples showcases the significance of preparation and clarity in technical, online communication. The well-explained question about sorted arrays brought forth thoughtful and detailed responses that improved the community’s collective knowledge. In constrast, the poorly constructed `Math.Cos` question led to a superficial conversation that resolved the immediate issue but missed an opportunity for broader understanding.

Raymond’s principles highlight the value in maintaining meaningful engagement. Smart questions save time, attracting collaborative problem-solving, generating insights that are most likely beneficial to others. On the other hand, the poorly framed questions waste the time of readers and often lead to less impactful answers.

## Insights
These examples reinforce the reason why smart questions should be asked. It showcases encouragement, proving that it is both a skill and a habit. It requires effort, preparation, and a genuine respect for the time and expertise of those who may respond to give insightful knowledge. By following the guidelines of Raymond’s principles, it helps maintain our questions to be clear, concise, and engaging. This will lead to a higher chance for a better outcome, including everyone involved. For software engineers, this methodical approach is crucial for professional growth, creating strong collaboration, and maintaining a strong foundation for the surrounding community.

## Conclusion
In conclusion, producing smart questions are a fundamental skill for software engineers. By providing thoughtful inquiries and considering Raymond's guidelines, we can improve our problem-solving capabilities and contribute to a culture with respect and shared learning. The opposing examples provided from Stack Overflow demonstrate how important Raymond’s principles are, leading to a more effective and meaningful interactions. If these principles are neglected, there is a higher chance of resulting in frustration and wasted effort in response. In the end, the approach to crafting questions shapes the quality of the answers we receive in return, including the depth of the connections we build.

## Acknowledgment
This essay was aided with AI tools for spelling, grammar, and structural polishing. 

