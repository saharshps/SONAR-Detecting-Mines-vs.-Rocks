## 🎯 1. Business Objective

**Goal:** To build an intelligent machine learning system that automatically detects whether an underwater sonar signal is reflected from a **metallic mine** (potentially dangerous) or a harmless **rock**.

This is vital for:

- **Maritime Safety:** Prevent ships and submarines from colliding with underwater mines.
- **Naval Defense:** Identify and safely remove underwater mines.
- **Resource Exploration:** Distinguish between useful metal structures and natural seabed objects.

---

## 📌 2. Problem Statement

In underwater environments, **Sonar (Sound Navigation and Ranging)** is used to detect objects. However, raw sonar signals can be noisy and difficult for humans to interpret consistently.

This dataset contains:

- **Total Samples:** 208 sonar returns
- **Metal Cylinders (Mines):** 111 samples
- **Rocks:** 97 samples
- **Features:** 60 numeric features per sonar return, each representing the energy of the signal in a specific frequency band.

The objective is to develop a machine learning classification model that accurately distinguishes between mines and rocks based on sonar signal patterns.
