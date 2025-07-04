# SDU x AAU GODOT Workshop

This repository contains code and materials developed for the **SDU x AAU GODOT Workshop**. The focus is on practical examples using the **ESA GODOT** (Generic Orbit Determination and Optimisation Toolkit) library through its Python interface.

---

## 📁 Contents

- `.pdf` files for the necessary steps and infos
- `data/` – Configuration files (e.g. `universe.yml`, `trajectory.yml`)
- `README.md` – This file with setup instructions and acknowledgements

---

## 🧩 Setup & Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/albertamarsanaa/SDU-x-AAU-GODOT-Workshop
    cd SDU-x-AAU-GODOT-Workshop
    ```

2. Create a virtual environment and install dependencies:

    ```bash
    python3 -m venv env
    source env/bin/activate
    pip install -r requirements.txt
    ```

3. Install or link the ESA GODOT library (≥ v1.11.0). Instructions available at:
   - [https://godot.io.esa.int/godotpy/](https://godot.io.esa.int/godotpy/)
   - [https://godot.io.esa.int/godotpy/tutorials/](https://godot.io.esa.int/godotpy/tutorials/)

---

## 📚 Acknowledgements

Some files in this repository are **directly obtained from the official ESA GODOT tutorial series**. These include examples such as:

- **eigen05c_80_sha.tab**
- **KourouStation.json**
- **Nutation2000A.ipf**
- **nga (2).csv**

The original files are publicly available and maintained by ESA:
- [https://godot.io.esa.int/tutorials](https://godot.io.esa.int/tutorials)

These materials are used here for educational and collaborative workshop purposes.

---

## 🔧 How to Use

- Launch any notebook under `notebooks/` to explore the GODOT use cases interactively.
- Modify configuration files to simulate custom mission scenarios.
- Use `scripts/` to run batch processes or generate reproducible results.

---

## 📜 License

This project is shared under the same terms as the ESA GODOT examples. For more details, refer to the license information provided by ESA or include a `LICENSE` file in this repository.

