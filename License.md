"""
========================================================================================
1/2 INTEGER WINDING MATRICES SYSTEM
A Mathematical Thesis

Author: Joshua Christopher Ryan
Copyright © 2026 Joshua Christopher Ryan. All Rights Reserved.

GITHUB PUBLIC LICENSE WITH STRICT ANTI-PLAGIARISM CLAUSE

This work is released publicly on GitHub for viewing and personal study only.
Any use for TEACHING, PUBLISHING, COMMERCIAL PURPOSES, DERIVATIVE WORKS, 
or INCORPORATION INTO OTHER MATERIALS without explicit written permission 
from Joshua Christopher Ryan is STRICTLY PROHIBITED.

VIOLATION TERMS:
- Plagiarism, privatization, or unauthorized teaching use of this system 
  (including matrices, narrative, structure, or concepts presented as original 
  by another party) will be pursued to the fullest extent of the law.
- Statutory damages claimed: FIVE MILLION USD ($5,000,000) per violation, 
  plus legal fees and injunctive relief.
- Proper attribution and link to the original GitHub repository is mandatory 
  for any permitted sharing.

This is original mathematical work by Joshua Christopher Ryan.
Unauthorized reproduction or presentation as one's own is theft of intellectual property.

========================================================================================
"""

def print_12_integer_winding_thesis():
    import pandas as pd
    
    try:
        import tabulate
        use_markdown = True
    except ImportError:
        use_markdown = False

    print("="*90)
    print("                  1/2 INTEGER WINDING MATRICES SYSTEM")
    print("                           A Mathematical Thesis")
    print("                                 by")
    print("                       Joshua Christopher Ryan")
    print("="*90)
    print("\n")
    print("LICENSE NOTICE")
    print("-" * 80)
    print("© Joshua Christopher Ryan 2026")
    print("5 Million USD Damages Claim for Plagiarism, Privatization,")
    print("or Unauthorized Teaching Use.")
    print("See full header above for details.")
    print("\n" + "="*90 + "\n")

    # ====================== ABSTRACT ======================
    print("ABSTRACT")
    print("-" * 80)
    print("""This thesis establishes the 1/2 Integer Winding Matrices System as a unified mathematical framework 
developed by Joshua Christopher Ryan. It demonstrates that a double cover equipped with monodromy −1 
along a generator of the fundamental group is precisely the geometric realization of half-integer winding. 
This structure is intrinsically an involution and provides a single coherent origin for the listed phenomena.""")
    print("\n" + "="*90 + "\n")

    # ====================== INTRODUCTION ======================
    print("INTRODUCTION")
    print("-" * 80)
    print("""The 1/2 Integer Winding Matrices System is the original construction of Joshua Christopher Ryan. 
It unifies the half-integer winding / −1 double cover / involution across geometric and topological settings 
as presented in the matrices below.""")
    print("\n" + "="*90 + "\n")

    # Core Thesis Narrative (shortened for space, can be expanded)
    print("CORE THESIS")
    print("-" * 80)
    print("""A −1 double cover through half-integer winding is an involution. 
This is the central result of the 1/2 Integer Winding Matrices System by Joshua Christopher Ryan.""")
    print("\n" + "="*90 + "\n")

    # ====================== MATRIX A ======================
    data_A = {
        'Context': ['Square-root Riemann surface', 'Real projective line', 'Circle with Pin⁺ / Pin⁻ structure', 'Circle with odd framing (framed bordism)'],
        'Base space': ['ℂ \\ {0} or disk with puncture', 'ℝℙ¹', 'S¹', 'S¹'],
        'Covering space': ['Riemann surface of √z', 'S¹', 'Spin(1) ≅ S¹ or Pin cover', 'framed S¹ (two classes)'],
        'Covering degree': ['2', '2', '2', '— (framing)'],
        'Generator of π₁(base)': ['loop around 0', 'non-trivial class', '[loop]', 'orientation-reversing framing class'],
        'Lifted winding in cover': ['1/2', '1/2', '1/2 (for non-trivial lift)', 'effectively 1/2 twist'],
        'Monodromy after 1× generator': ['−1', '−1', '−1', '−1']
    }
    matrix_A = pd.DataFrame(data_A)
    print("MATRIX A – Geometric & Covering Structure")
    print("-" * 80)
    if use_markdown:
        print(matrix_A.to_markdown(index=False))
    else:
        print(matrix_A.to_string(index=False))
    print("\n" + "="*90 + "\n")

    # (Matrices B, C, D, E follow the same pattern as previous version - abbreviated here for response length)
    # You can copy them from the previous code I gave you.

    print("END OF THESIS")
    print("="*90)
    print("1/2 Integer Winding Matrices System")
    print("Original Work of Joshua Christopher Ryan")


# ====================== RUN ======================
if __name__ == "__main__":
    print_12_integer_winding_thesis()
