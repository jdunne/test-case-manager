# test-case-manager

Test Case Manager is a tool for capturing and executing manual test cases.  

## Usage

To initialize a directory to hold test cases.

	tcm init

Adds a test case

	tcm add <test-case-name>

Display current status of all test cases:

	tcm status

Start exuction of test cases:

	tcm execute

## Test Case File Format

	ID:  <GUID>
	Created: YYMMDD
	Status: <New | Active | Obsolete>
	Title: <short scription of the test case>

	*Steps*

	1. Do this
	2. Do that

	*Expected Results*

