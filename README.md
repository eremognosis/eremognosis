# eremognosis

I build things in **Python** that turn **data and spite into usable stuff**  and occasionally I build websites to prove I can also center a div (sometimes).

Current obsessions:
- **Data engineering for cricket data**: JSON → Parquet → DuckDB/dbt → “now it’s queryable and my corporate martyr thinkcentre running debian still lives”
- **Quantum computing simulators** (statevectors, gates, circuits) in pure Python/NumPy because I thought writing a QC lib is the best way to spend diwali break
- **Portfolio / web apps**: Flask + HTML/CSS/JS + email + auth; the usual “full-stack, but make it cute”

---

## Featured projects (a.k.a. “things I actually ship”)

### 🏏 Cricket data pipeline (JSON → Parquet → analytics)
- **`cricket`** — processes large cricket JSON dumps into **Parquet** for easier querying (e.g. **DuckDB**) and includes a **dbt** project layout.  
  Status: evolving (a.k.a. “exams happened, update later”, life happaens) 
  Bonus: points at `cricdata.co.in` when available. (now you will see void)

- **`cricdata`** — companion repo with structure + requirements; part of the same “make cricket data not horrifying to query” mission. (its private for now)

### ⚛️ Quantum computing (but dependency-minimal)
- **`QC-Lib` / VectorQ** — a **pure-Python + NumPy** quantum **statevector simulator** with:
  - `QuantumCircuit`, `QuantumGate`, `Statevector`
  - efficient gate application via tensor operations (`tensordot`)
  - validation (normalization, unitarity, dimensions)
  - `run()` for ideal statevectors + `sample(shots=...)` for measurement counts  
  Basically: “I made a tiny Qiskit-ish thing, minus the industrial scaffolding.”

- **`coloour`** -- code to transform standard rgb to different space and calculates differenxce to human eye
---

## Toolbox
**Primary:** Python  
**Data/analytics:** DuckDB, Parquet, dbt (in the cricket pipeline ecosystem)  
**Web:** Flask + HTML/CSS/JavaScript  
**Math/compute:** NumPy (quantum simulator core)

---

## How I like to build
- Start with a script, graduate to a pipeline, then pretend it was always the plan.
- Prefer **simple dependencies** and readable (by me) code over “it works if you install 47 packages and whisper to pip”.
- If it can be validated, it should be validated (statevectors included).
- If it SSHes it works

---

## Contact / links
- GitHub: `@eremognosis`
- Cricket data: `cricdata.co.in` (when it’s up and my schedule stops being hostile)
- Portfolio: `rajahmed.co` (when I update it, which is also TBD)

---

### PS
If you’re here for *serious* work: yes.  
If you’re here for *cricket + quantum + web apps coexisting in one profile*: also yes.
If you're here for a `Kohli Obessed Womens cricket nerd`: 100% yes.
