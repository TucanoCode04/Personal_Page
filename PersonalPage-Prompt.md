Open `C:\Users\donat\Desktop\PersonalPage\Personal_Page` in VS Code, start Claude Code there and paste the prompt below.

---

Update my personal page (`index.html`, served by GitHub Pages at tucanocode04.github.io/Personal_Page/). Keep the current design, style and section structure; only change content and add what's listed. My CV is the source of truth: `Curriculum-Vitae-Quantum.pdf` (software) and `Curriculum-Vitae-Quantum-Hardware.pdf` (hardware) are now in the repo root.

1. **CV downloads:** every "Download CV" button must point to `Curriculum-Vitae-Quantum.pdf`. Next to the main button, add a smaller secondary link "Hardware CV" pointing to `Curriculum-Vitae-Quantum-Hardware.pdf`. Remove references to `Curriculum-Vitae-EN.pdf` and delete that file.
2. **Intro/About:** say I'm looking for a 6-month quantum internship (software or hardware) starting February/March 2027, possibly leading to my Master's thesis. Mention my main areas: error mitigation, compilation/routing, quantum networks, qubit control electronics (FPGA/RFSoC), HPC.
3. **Languages:** match the CV: Italian (native), English C2, Spanish **B2**, German B1.
4. **Experience:**
   - QubiTO: add "Built the website of the Qubito Quantum Hackathon 2026 (main partner: IQM) and helped develop the team's main site", with a link to https://qubito.polito.it/hackathon/
   - Add **Quantum Code Reviewer, PQID-Bench** (Sep–Oct 2026): reviewed AI-generated Qiskit code for correctness and physical plausibility, contributing to the benchmark.
   - Add **Hackathons:** QHack (PennyLane) participant; PushQuantum 2026 (Munich).
5. **Projects:** put the quantum projects first, as cards linking to the GitHub repos:
   - **ML for Quantum Error Mitigation** (2026–present), https://github.com/TucanoCode04/ML-for-Quantum-Error-Mitigation: reproducing Liao et al. (2023), random-forest and linear models that predict ideal ⟨Zᵢ⟩ from noisy results, on IQM backends.
   - **qnet, quantum-repeater simulator** (2026), https://github.com/TucanoCode04/qrepeater: modular NetSquid simulation of entanglement swapping, validated against analytic models with pytest.
   - **Noise-aware qubit routing compiler** (2026), https://github.com/TucanoCode04/QuantumHardware_lab03: Qiskit routing with error-weighted shortest paths and lookahead, benchmarked on standard QASM circuits.
   - **Qubit Electronics Lab** (2026): FPGA/RFSoC work, Poisson–Schrödinger simulation of a SiMOS quantum dot with gate-barrier tuning.
   - **Quantum Technologies Lab** (2026), https://github.com/TucanoCode04/Lab1-Quantum-Technologies: BB84 QKD demonstration, single-photon detectors (SPAD) and backflash security.
   - **HPC Project** (2026), https://github.com/TucanoCode04/HPC_Exam_Project_01: wave simulation with OpenMP, MPI and CUDA on Politecnico's cluster, profiled with VTune and Nsight.
   - Keep the bachelor's thesis. Move the older course projects (Chesscake, Selfie, PandOS, Programming Game) into a compact "Other projects" row underneath.
6. **Skills section (new, short):** quantum (Qiskit, PennyLane, NetSquid, IQM), hardware (FPGA, RFSoC, LTspice, quantum-dot simulation), HPC (OpenMP, MPI, CUDA, SLURM), programming (Python, C/C++, MATLAB, Java), ML (scikit-learn, TensorFlow/Keras).
7. **Contact:** add LinkedIn (https://www.linkedin.com/in/davide-donati-82992133b/) and GitHub (https://github.com/TucanoCode04) as visible links/icons, not only email and phone.
8. **Meta:** set a `<meta name="description">` and Open Graph tags (title "Davide Donati – Quantum Engineering", short description), so the link previews nicely on LinkedIn.
9. **Cleanup:** delete `index-old.html` and `redesign.html` if nothing links to them. Compress `favicon.png` (it's 1.4 MB; a 64×64 or 180×180 PNG is enough).
10. Check that the page works on a phone screen (people will open it from a QR code on my CV) and that every link works.

When done, show me a summary of the changes. Don't commit or push; I'll review first.
