# Pharos Docs MCP + Chain MCP Agent

An intelligent agent developed in **Java** for the Pharos Agent Arena that bridges documentation lookup (Docs MCP) with on-chain execution (Chain MCP)[cite: 4].

## 📋 Requirements Met

1. **Docs MCP Integration (Req. 01):** Retrieves detailed function explanations accompanied by referenced documentation URLs[cite: 4].
2. **Chain MCP Execution (Req. 02):** Executes the corresponding smart contract function on-chain[cite: 4].
3. **Contextual Interpretation (Req. 03):** Interprets the execution output directly within the scope of the retrieved technical documentation[cite: 4].
4. **Multi-Function Support (Req. 04):** Successfully handles at least two distinct functions across different smart contracts[cite: 4].

## 🚀 How to Run

1. Make sure you have **Java JDK** installed.
2. Compile the file:
   ```bash
   javac DocsChainAgent.java
