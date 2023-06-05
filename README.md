# Wumpus World Solver using DPLL and Python Knowledge Base

This repository contains a Python implementation of a Wumpus World solver using the DPLL (Davis–Putnam–Logemann–Loveland) algorithm and a knowledge base.

## What is the Wumpus World?

The Wumpus World is a classic artificial intelligence problem in which an agent (usually represented by a player) navigates a grid-based world filled with hazards, such as pits and a Wumpus (a dangerous creature). The goal of the agent is to find the gold without falling into any pits or getting eaten by the Wumpus.

## How does the Solver Work?

The solver in this repository utilizes the DPLL algorithm, a powerful technique for solving propositional satisfiability problems (SAT). The DPLL algorithm systematically explores the possible assignments of truth values to the propositional variables in order to find a satisfying assignment, if one exists.

The solver constructs a knowledge base that represents the current state of the Wumpus World. It uses logical inference rules and deductions to update the knowledge base as the agent explores the environment. The DPLL algorithm is then applied to the knowledge base to find a satisfying assignment of truth values, which provides the solution to the Wumpus World problem.

