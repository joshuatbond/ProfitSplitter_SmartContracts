# Profit Splitting with Smart Contracts

## Overview

A new startup has created its own Ethereum-compatible blockchain to help connect financial institutions, and their team wants to build smart contracts to automate some company finances to make everyone's lives easier, increase transparency, and to make accounting and auditing practically automatic!

To aid in this effort, we will be creating profit splitting smart contracts. These contracts will do the following:

* Pay your Associate-level employees quickly and easily.
* Distribute profits to different tiers of employees.

## Associate Profit Splitting Smart Contract

The simplest of the two smart contracts. This contract allows the company to pay 3 employees equal amounts, as well as send the amounts to each employee's specific address.

In the event of a remainder being left over after the even split, this contract will then send the remaining amount back to the sender (owner) of the contract.

In other words, this contract will allow the HR department to pay employees quickly and efficiently.

## Tiered Profit Splitting Smart Contract

Building on the design of the associate profit splitting contract, this smart contract adds a degree of customizability.

In this contract, one has the ability to assign different percentages of pay according to different employee tiers/levels. For example, the CEO can be paid 60%, CTO 25%, and an additional employee 15%. As in the previous contract, these amounts will be sent directly to each of the employees' specific addresses. However, unlike in the previous contract, any remaining balance after the split will be sent to the highest teired/ranking employee.
