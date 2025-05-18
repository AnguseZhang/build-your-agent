# build-your-agent

An open project initiated by the DeepModeling community focused on constructing intelligent agents for scientific research. It is committed to assembling a reusable and extensible set of Agent-Ready tools, promoting the development and practical deployment of research agents through open collaboration.

We Encourage Community Contributions:

- 🤖 **Co-construction Platform for Agent Tools**:  
  Collecting a variety of Agent-Ready tool modules (Tool/Plugin/API/Function)

- 🧠 **Incubator for Agent Development**:  
  Sharing intelligent agent examples built with toolchains to solve real scientific research problems

- 👥 **Learning and Exchange Hub for Agent Creators and Researchers**:  
  Providing beginner-friendly, runnable tutorials for using agents and connecting developers, AI engineers, and scientific researchers


Whether you're a researcher, developer, or a curious learner passionate about AI for Science, you're welcome to join us in building an agent ecosystem for the future of science!

# Project Plan

## Phase 1: Collection and Adaptation of Agent-Ready Tools (By 2025/6/15)

**Goal:**  
Build a high-quality, callable library of scientific tools to empower agents with executable capabilities that can be readily invoked.

**Key Tasks:**
- Validate tool-wrapping standards (MCP protocol / I/O specifications / documentation format / API format)
- Collect and adapt commonly used scientific tools (simulators, analysis scripts, plotting utilities, etc.)
- Publish the initial tool index (Tool Index + example invocation code)

**Example Target Tools:**
- Interfaces: DeePMD / ABACUS / GPUMD / ASE / LAMMPS / GROMACS
- Python toolchains: pymatgen / RDKit / scikit-learn

---

## Phase 2: Agent Template Development and Standardization (By 2025/7/5)

**Goal:**  
Develop reusable agent design paradigms to facilitate engineering-grade agent development.

**Key Tasks:**
- Define and validate a reference architecture for “scientific research agents”  
  *(Perception → Planning → Execution → Feedback)*
- Build exemplar agents for typical scientific scenarios:
