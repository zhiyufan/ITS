<!-- ## Workflow -->

The following steps show the intended workflow through the Intelligent Tutoring System (ITS). Note that there are points of variation (static and dynamic) that depend, e.g., on the programming language of the programming assignments and the intended repair strategies. Many of the current components can be implemented in many different ways.


## Overview
![ITS-workflow](../icons/workflow/0_overview.svg)

The Intelligent Tutoring System (ITS) uses the notion of a pipes-and-filter style to process the submitted program and, finally, to produce feedback for the students and a grading report for the tutor.
 
All components provide corresponding interfaces to the extent that most components can be implemented independently from each other.

This architecture also allows us to deploy specific system components as separate services. In this regard, the design borrows concepts from the service-oriented style. For example, we provide students with access to a Parser service that allows them to easily generate the internal CFG-based Program representation to create test cases for their projects.

## Step 1: Parser
![ITS-workflow](../icons/workflow/1_parser.svg)

## Step 2: Syntactic Alignment
![ITS-workflow](../icons/workflow/2_alignment.svg)

## Step 3: Error Localizer
![ITS-workflow](../icons/workflow/3_errorlocalizer.svg)

## Step 4: Interpreter
![ITS-workflow](../icons/workflow/4_interpreter.svg)

## Step 5: Repair
![ITS-workflow](../icons/workflow/4_repair.svg)

## Step 6: Feedback
![ITS-workflow](../icons/workflow/6_feedback.svg)

## Step 7: Concretization
![ITS-workflow](../icons/workflow/7_conretization.svg)

## Step 8: Auto-Grading
![ITS-workflow](../icons/workflow/8_grading.svg)