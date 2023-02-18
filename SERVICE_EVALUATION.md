Service Assessment Guidelines 
=============================
The cross-validation of services is an important step in the process of developing an A/D CTF. These guidelines provide a high-level overview of the steps that should be taken when performing the assessment. They cover key areas such as compliance of the project structure, correspondance between the service documentation and the actual implementation, intended functionalities, correctness of the checkers, effectiveness of provided exploits and patches.

1. Project Structure
   - Ensure that the project structure follows the [Service Development Guidelines](SERVICE.md)

2. Correspondence between the documentation and the actual implementation
   - Verify that the implementation of the service accurately follows the design provided in the `README.md` file
   - Ensure that all described flag stores and features are present in the service

3. Evaluation of Intended Functionalities
   - Test the service to confirm that it supports the intended functionalities as described in the documentation
   - Attempt to interact with the service in unexpected ways to see if there are any unintended behaviors or vulnerabilities

4. Testing the Checkers
   - Test the checkers for all flag stores found in the service
   - Ensure that checkers are working as intended for several rounds and that they return the correct status code depending on the service state
   - Test that by deleting recent flags, running the checker returns the `RECOVERING` status
   - Ensure that checkers are covering enough intended functionalities of the service (this should be done by the `check_service` function)

5. Testing the Effectiveness of Provided Exploits
   - Attempt to exploit the service using the provided exploits to confirm their effectiveness
   - Try to find additional vulnerabilities in the service that are not covered by the provided exploits

6. Testing the Correctness of Provided Patches
   - Verify that the patches provided for the service fix the vulnerabilities that they were intended to fix
   - Check that the patches do not introduce any new vulnerabilities or break any intended functionality
   - Test the service with the provided patches to ensure that it continues to perform as expected

Note:
* If you have access to the original repostiroy of the tested service, we advise reporting all encountered problems by opening individual issues (1 issue = 1 problem). Try to be constructive and support the developers as much as possible to close the issue.
* Keep in mind that this is a high-level guide, and each CTF service is different and will have its specificities that need to be considered when performing the evaluation.