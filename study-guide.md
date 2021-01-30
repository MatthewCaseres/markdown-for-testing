# Midterm 1 Study Guide

## DAC

Which Type of control is based on the identity of the requestor and the access rules state what a requestor can or cannot do?

- A) Mandatory Access Control (MAC)
- B) Role-based access control (RBAC)
- C) Discretionary access control (DAC)
- D) Attribute-based access control (ABAC)

<details type="mcq">
<summary>Answer</summary>
C. This policy is termed discretionary because an entity might have access rights that permit the entity, by its own volition, to enable another entity to access some resource.
<br />
<br />
Source: Book Chapter 4.2 Page 131
</details>



What data structure is typically used to implement DAC?

- A) Linked List
- B) 2 Dimensional Matrix
- C) Red Black Tree
- D) Stack

<details>
<summary>Answer</summary> B

Source: Book Chapter 4.3 Page 111
</details>



Access Control Lists make it easy to look up who all the users are that can access a resource, and the type of access they have for that resource.

True or False?

<details>
<summary>Answer</summary>  True

Source: Book Chapter 4.3 Page 111
</details>



Question: What does each entry of an access matrix indicate?

- A. Access rights of a particular object for a particular subject.
- B. Access rights of a particular subject for a particular object.
- C. Access rights of a particular subject for a particular directory.
- D. Access rights of a particular object for a particular group.

<details>
<summary>Answer</summary>  B.

Source: Book pg. 111
</details>



(True/False) DAC is a concept that evolved out of requirements for military information security.

<details>
<summary>Answer</summary>  False, DAC is the traditional method for implementing access control, MAC was created out of military necessity.

Source: Book, Ch 4, Pg. 109
</details>



(True/False) One problem with DAC is that it is not possible to control information flow.

<details>
<summary>Answer</summary>  True

Source: Mandatory Access Control Lecture
</details>



(True/False) DAC is popular with corporations because it reflects how they treat their data.

<details>
<summary>Answer</summary>  False. Employers mandate explicit policies on who can share what.

Source: Mandatory Access Control Lecture
</details>

## Program/Host Privileges -- Program control flow

Put the following statements, regarding the sequence of calls made made by a function call to the stack, in the correct order:

- A. Allocate space for local variables by moving the stack pointer down to leave sufficient room for them.
- B. Push the parameters for the called function onto the stack.
- C. Run the body of the called function.
- D. Execute the return function which pops the saved address off the stack and returns control to the calling function.
- E. Push the current frame pointer value (which points to the calling routine's stack frame) onto the stack.
- F. Executes the call instruction to call the target function, which pushes the return address onto the stack.
- G. Pops the old frame pointer value (restoring the link to the calling routine's stack frame).
- H. Sets the frame pointer to be the current stack pointer value, which now identifies the new stack frame location for the called function.
- I. Set the stack pointer back to the value of the frame pointer.

<details>
<summary>Answer</summary>
B, F, E, H, A, C, I, G, D

From text pg 327.
</details>

## Access control mechanisms

An access control mechanism mediates between a user (or a process executing on behalf of a user) and system resources, such as:

- a) firewalls
- b) routers
- c) applications
- d) a & b only
- f) All of the above

<details>
<summary>Answer</summary>
f) All of the above

Textbook, Chapter 4, pg. 108
</details>