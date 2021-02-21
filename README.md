# QOSFMentorshipProgram_ScreeningTask2
This is a solution to the second problem in the third QOSF Mentorship Program

Just run the notebook from up to the bottom.

In the question 3, I propose a different correcting code using the stabilizers formalism. The set of possible message is stabilized by X1X2 and Z1Z2 so if we measure this in this basis, we can diagnose the error without destroying the state. However, since I'm not sure how to use measurement in X1X2 and Z1Z2, I use CNOT gate. The idea is that we compare each two qubits to see if it's the same or not. The ancilla bit are using for that purpose.   
