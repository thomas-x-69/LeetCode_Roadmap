<details>
<summary>🌈 Click to reveal awesome table! 🚀</summary>

<table>
  <tr>
    <th colspan="3" style="background-color: #4CAF50; color: white; font-size: 16px; font-weight: bold; text-align: center; padding: 10px; border: 2px solid #4CAF50;">🌟 Super Awesome Table 🌟</th>
  </tr>
  <tr>
    <th style="background-color: #2196F3; color: white; padding: 10px; border: 1px solid #1976D2;">Header 1 📊</th>
    <th style="background-color: #FFC107; color: black; padding: 10px; border: 1px solid #FFA000;">Header 2 💡</th>
    <th style="background-color: #E91E63; color: white; padding: 10px; border: 1px solid #C2185B;">Header 3 🎨</th>
  </tr>
  <tr>
    <td style="background-color: #E3F2FD; padding: 10px; border: 1px solid #90CAF9;">
      <details>
        <summary>Expand for cool stuff!</summary>
        <ul>
          <li>Item 1 🔥</li>
          <li>Item 2 ⚡</li>
        </ul>
      </details>
    </td>
    <td style="background-color: #FFF9C4; padding: 10px; border: 1px solid #FFF176;">
      <img src="https://github.githubassets.com/images/icons/emoji/octocat.png" alt="Octocat" width="50"><br>
      GitHub Octocat!
    </td>
    <td style="background-color: #FCE4EC; padding: 10px; border: 1px solid #F48FB1;">
      <code>console.log("Hello!")</code>
    </td>
  </tr>
  <tr>
    <td style="background-color: #E8F5E9; padding: 10px; border: 1px solid #A5D6A7;">
      <a href="https://github.com">GitHub Link</a>
    </td>
    <td style="background-color: #FFECB3; padding: 10px; border: 1px solid #FFD54F;">
      <blockquote>Inspiring quote here!</blockquote>
    </td>
    <td style="background-color: #F3E5F5; padding: 10px; border: 1px solid #CE93D8;">
      <details>
        <summary>Task List</summary>
        <ul>
          <li>[ ] Task 1</li>
          <li>[x] Task 2</li>
        </ul>
      </details>
    </td>
  </tr>
</table>

</details>
# Project Name
![Version](https://img.shields.io/badge/version-1.0.0-blue)

## Roadmap
```mermaid
graph TD
    A[DSA Roadmap]
    A --> B[1. Arrays/String]
    B --> C[2. Hashing]
    C --> D[3. Two Pointers]
    D --> E[4. Sliding Window]
    E --> F[5. Stack]
    F --> G[6. Binary Search]
    G --> H[7. Linked List]
    H --> I[8. Trees]
    I --> J[9. Backtracking]
    J --> K[10. Graphs]
    K --> L[11. Heaps]
    L --> M[12. Dynamic Programming]
    M --> N[13. Intervals]
    N --> O[14. Tries]
    O --> P[15. Greedy]
    P --> Q[16. Bit Manipulation]
    Q --> R[17. Math]

    subgraph SG1[" "]
        direction TB
        C1[Prefix Sum]
    end
    C --- SG1

    subgraph SG2[" "]
        direction TB
        D1[Warmup]
        D2[Running from both ends of an array]
        D3[Caterpillar]
        D4[Running from beginning of 2 arrays]
        D5[Others]
        D1 --> D2 --> D3 --> D4 --> D5
    end
    D --- SG2

    subgraph SG3[" "]
        direction TB
        E1[Fixed Size]
        E2[Variable Size]
        E1 --> E2
    end
    E --- SG3

    subgraph SG4[" "]
        direction TB
        F1[Parentheses push & pop]
        F2[Next Greater Element]
        F1 --> F2
    end
    F --- SG4

    subgraph SG5[" "]
        direction TB
        G1[Rotated Binary Search]
        G2[Minimum and Maximum Sum Type]
        G3[Two Array Types]
        G4[Design]
        G1 --> G2 --> G3 --> G4
    end
    G --- SG5

    subgraph SG6[" "]
        direction TB
        H1[Basic Operations]
        H2[2 or more LL]
        H3[Fast Pointer Slow Pointer]
        H4[Design]
        H1 --> H2 --> H3 --> H4
    end
    H --- SG6

    subgraph SG7[" "]
        direction TB
        I1[Construction and Modification]
        I2[Binary Search Tree BST Operations]
        I3[Path Problems]
        I4[Tree Properties and Metrics]
        I5[Tree Comparison]
        I6[Ancestor Problems]
        I1 --> I2 --> I3 --> I4 --> I5 --> I6
    end
    I --- SG7

    subgraph SG8[" "]
        direction TB
        J1[Permutations]
        J2[Combinations]
        J3[Subset]
        J1 --> J2 --> J3
    end
    J --- SG8

    subgraph SG9[" "]
        direction TB
        K1[BFS]
        K2[DFS]
        K3[Connected Components]
        K4[Dijkstra's Algorithm]
        K5[Union Find]
        K6[Minimum Spanning Tree]
        K7[Topological Sort]
        K8[Floyd Warshall Algorithm]
        K9[Bellman Ford Algorithm]
        K10[Graph Coloring]
        K1 --> K2 --> K3 --> K4 --> K5 --> K6 --> K7 --> K8 --> K9 --> K10
    end
    K --- SG9

    subgraph SG10[" "]
        direction TB
        L1[Sorting]
        L2[Heap Pop]
        L3[Kth Largest/Smallest Element]
        L4[Design]
        L5[Sweep Line]
        L6[Advanced Heap]
        L1 --> L2 --> L3 --> L4 --> L5 --> L6
    end
    L --- SG10

    subgraph SG11[" "]
        direction TB
        M1[Linear DP]
        M2[Knapsack]
        M3[Multi Dimensions DP]
        M4[Interval DP]
        M5[Bit DP]
        M6[Digit DP]
        M7[DP on Trees]
        M8[String DP]
        M9[Probability DP]
        M10[Classic DPs]
        M11[DP + Alpha Tricks/DS]
        M12[Insertion DP]
        M13[Graph DP]
        M14[Memoization]
        M15[Binary Lifting]
        M16[Math]
        M1 --> M2 --> M3 --> M4 --> M5 --> M6 --> M7 --> M8 --> M9 --> M10 --> M11 --> M12 --> M13 --> M14 --> M15 --> M16
    end
    M --- SG11

    subgraph SG12[" "]
        direction TB
        P1[Sorting]
        P2[Two Pointer]
        P3[Heap]
        P4[Miscellaneous]
        P1 --> P2 --> P3 --> P4
    end
    P --- SG12

    subgraph SG13[" "]
        direction TB
        Q1[Basic Properties of XOR]
        Q2[DP + Bitmasks]
        Q3[Generating Submasks of a Bitmask]
        Q4[Misc]
        Q1 --> Q2 --> Q3 --> Q4
    end
    Q --- SG13

    subgraph SG14[" "]
        direction TB
        R1[Basic Math]
        R2[Matrix]
        R1 --> R2
    end
    R --- SG14
```
<!-- another alternative>

```mermaid

mindmap
  root((DSA Roadmap))
    Arrays & Hashing
      Two Pointers
        Binary Search
        Sliding Window
        Linked List
      Stack
    Trees
      Tries
      Backtracking
        Graphs
        1-D DP
      Heap / Priority Queue
        Intervals
        Greedy
        Advanced Graphs
        2-D DP
        Bit Manipulation
          Math & Geometry
```
<!-- another alternative-->
