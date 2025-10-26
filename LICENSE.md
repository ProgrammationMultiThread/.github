# Global License and Attributions

This file applies to all repositories under the **ProgrammationMultiThread** organization.  
Each repository includes its own [`LICENSE.txt`](../<repo>/LICENSE.txt) containing the full legal text of its primary license (MIT for code, CC BY-SA 4.0 for teaching materials).

**Author:** Matthieu Perrin  
**Copyright:** © 2025 Matthieu Perrin

---

## LaTeX files (`.tex` and `.sty`)

Except where otherwise noted, all **original LaTeX teaching materials and derived PDF files** in this repository (slides, LaTeX sources/macros, etc.) are licensed under **CC BY-SA 4.0**.  

You are free to **share** and **adapt** the material for any purpose, even commercially, under these terms:
- **Attribution** — Give appropriate credit, provide a link to the license, and indicate if changes were made. Attribution should be given in a *reasonable* manner (for presentations, a title or credits slide is recommended).
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the **same license**.

> CC licenses do not affect patent or trademark rights and may not grant all permissions necessary for your intended use. No warranties are given.

- **License summary:** <https://creativecommons.org/licenses/by-sa/4.0/>  
- **Full legal code:** <https://creativecommons.org/licenses/by-sa/4.0/legalcode>

### Suggested attribution example

> "*Programmation Concurrente en Multi-Threads* —  
> © 2025 Matthieu Perrin, CC BY-SA 4.0, no changes."  
(or describe changes if you made any).

---

## Java source code (`.java`)

Unless otherwise stated in the file header, all **Java source code and related project files** are distributed under the **MIT License**.

All Java projects within this organization (e.g. `Java-snippets/`, `TP-webgrep/`, `TP-mandelbrot/`, `TP-transactional-memory/`) include their own [`LICENSE.txt`](../Java-snippets/LICENSE.txt) file containing the full MIT License text.

This license applies only to the **original Java code** provided as part of the *Programmation Concurrente en Multi-Threads* course at Nantes Université.  
External libraries and dependencies (e.g. JSoup, JUnit) are distributed under their own respective licenses.

- **Full legal code:** <https://opensource.org/license/mit/>

### Suggested attribution

> "Source code from the course *Programmation Concurrente en Multi-Threads* —  
> © 2025 Matthieu Perrin, licensed under the MIT License."

---

## Images

Images in the various `src/img/` folders are subject to different licenses, listed below.  
Please verify third-party licenses before redistributing compiled PDFs that include those images.

### Original illustrations

The following images are **original works** by the author of the project and are licensed under the **Creative Commons Attribution–ShareAlike 4.0 International** (CC BY-SA 4.0).

- `CM/src/img/TP_Mandelbrot.png`
- `CM/src/img/TP_WebGrep.png`
- `Exercises/src/img/mandelbrot_running.png`

### AI-generated images (DALL·E)

The following illustrations were generated using **OpenAI's DALL·E** model.

These images are **original works** created by the project author (Matthieu Perrin) using prompts designed specifically for educational purposes.
They are released under the same license as the rest of this repository (**CC BY-SA 4.0**), unless otherwise noted.

DALL·E output is not subject to any additional copyright or usage restrictions beyond those of this project’s license.

- `CM/src/img/Alice.png`
- `CM/src/img/Bob.png`
- `CM/src/img/Carole.png`
- `CM/src/img/bakery.png`
- `CM/src/img/pupies_practice.jpg`
- `CM/src/img/pupies_theory.jpg`
- `CM/src/img/deadlock.jpg`
- `CM/src/img/starvation.jpg`

### External illustrations

The following images are **not part of the project** and are shared according to their own license.

- `CM/src/img/multicore.jpg` — **copyright** — Advanced Micro Devices, Inc. (AMD). Usages allowed with attribution by the copyright holder  
  <https://commons.wikimedia.org/wiki/File:Quad-Core_AMD_Opteron_processor.jpg>
- `CM/src/img/Lamport.jpg` — **CC-0** — Usages allowed for any purpose  
  <https://commons.wikimedia.org/wiki/File:Leslie_Lamport.jpg>
- `CM/src/img/Amdahl.jpg` — **CC-BY-3.0 unported** — Perry Kivolowitz (2008)  
  <https://commons.wikimedia.org/wiki/File:Amdahl_march_13_2008.jpg>
- `CM/src/img/Dijkstra.jpg` — **CC-BY-SA-3.0 unported** — Hamilton Richards (2002)  
  <https://commons.wikimedia.org/wiki/File:Edsger_Wybe_Dijkstra.jpg>
- `CM/src/img/Hansen.jpg` — **copyright** — Per Brinch Hansen (1999). Usages allowed with attribution by the copyright holder  
  <https://commons.wikimedia.org/wiki/File:Per_Brinch_Hansen_-_1999.jpg>
- `CM/src/img/Hoare.jpg` — **CC-BY-SA-2.0 France** — Rama (2011)  
  <https://commons.wikimedia.org/wiki/File:Sir_Tony_Hoare_IMG_5125.jpg>

### Third-party trademarks (logotypes)

The following logo is a **simple word or symbol mark** that does not meet the originality threshold for copyright protection  
(public domain, see [Wikimedia Commons – Threshold of originality](https://commons.wikimedia.org/wiki/Commons:Threshold_of_originality)).
It **remains a registered trademark** of its respective owner.

- `Exercises/src/img/logoUN.png` — **trademark* of Nantes Université  
  <https://www.univ-nantes.fr/medias/photo/logotype-nantes-u-noir-72dpi_1638965800927-png>

### Images not included in the repository

The following images are **not stored in this repository** and are **not redistributed** in compiled artifacts. They are downloaded locally at build time or referenced by URL for educational, non-commercial use under the applicable local copyright exceptions (e.g., fair use or fair dealing).

- `CM/src/img/time.png` — IT Hare  
  <http://ithare.com/wp-content/uploads/part101_infographics_v08.png>

---

## Acknowledgments and Sources

Some teaching material in this organization (e.g. exercises, code snippets or raw data) is **inspired by or adapted from** external sources such as in textbooks or research articles on concurrent programming.  
All statements have been **translated, rewritten, and contextualized** for educational use, without verbatim reproduction of any protected material.  
When a specific source is closely followed, it is **explicitly acknowledged** in the file header or in a footnote within the derived pdf material.

### Exercises

- `Exercises/src/exercises/blocking/philosophers.tex` — Inspired from  E. W. Dijkstra, *Hierarchical ordering of sequential processes*. Acta informatica (1971).
- `Exercises/src/exercises/introduction/mad.tex` — Inspired from M. Herlihy, N. Shavit. *The Art of Multiprocessor Programming*. Morgan Kaufmann (2008).
- `Exercises/src/exercises/monitors/savages.tex` — Inspired from G. R. Andrews. *Foundations of Multithreaded, Parallel, and Distributed Programming*. Addison-Wesley (2000).
- `Exercises/src/exercises/monitors/unisex.tex` — Inspired from A. B. Downey. *The Little Book of Semaphores*. Green Tea Press (2008).

### Java code

The following files are adapted from the example "Deadlock" in the official [Oracle Java Tutorials on Concurrency](https://docs.oracle.com/javase/tutorial/essential/concurrency/deadlock.html).  
Redistribution allowed with attribution (Oracle license terms).
- `Java-snippets/src/main/java/snippets/liveness/Friend.java`
- `TP-concurrence/src/main/java/concurrence/Friend.java`

The following files are inspired from Thibault Delor's [InvalidCodeBlog project](https://github.com/t-botz/InvalidCodeBlog/blob/master/src/main/java/com/invalidcodeexception/experiment/volatilekeyword/VolatileTest.java).
These files are *substantially modified* versions of the original example. They differ in structure, variable naming, and experimental setup, and should be considered **distinct original works** inspired by the source above.
- `Java-snippets/src/main/java/snippets/memory/Volatile.java`
- `TP-concurrence/src/main/java/concurrence/Volatile.java`

The following file is inspired from Datsabk's blog post on [Mkyong.com](https://mkyong.com/java/java-thread-mutex-and-semaphore-example/).
These files are *substantially modified* versions of the original example. They differ in structure, variable naming, and experimental setup, and should be considered **distinct original works** inspired by the source above.
- `TP-concurrence/src/main/java/concurrence/CountingSemaphore.java`

### External data

The data files in `CM/src/plot/*.dat` originate from the infographic *50 Years of Microprocessor Trend Data*, part of the **Microprocessor Trend Data** project by Karl Rupp, licensed under **CC BY 4.0**. The original dataset was compiled and collected by M. Horowitz, F. Labonte, O. Shacham, K. Olukotun, L. Hammond, C. Batten, and K. Rupp.

The presentation, formatting, and plotting scripts (e.g. `.gnuplot` files) were **originally created** for integration into this course and are licensed under the same terms as the LaTeX material (**CC BY-SA 4.0**).

- `CM/src/plot/*.dat` — **CC-BY-4.0** — Karl Rupp (2022)  
  <https://github.com/karlrupp/microprocessor-trend-data/>
- `CM/src/plot/microprocessor-trend.gnuplot` — **CC-BY-SA-4.0** — Matthieu Perrin (2025)

