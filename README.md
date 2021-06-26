<div>
  <h1 align="center">dhat-profiler-viewer</h1>
  <h4 align="center">
    A fork from Valgrind's DHAT (Dynamic Heap Allocation Tool) Profiler
    Viewer v3.17.0 for inspecting dhat-rs reports
  </h4>
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/EstebanBorai/dhat-profiler-viewer/main/docs/Screenshot%202021-06-25%20at%2021-33-38%20DHAT%20Viewer%20-%20dhat-heap%20json%20-%20Total%20(blocks).png" width="700" />
</div>

## Motivation

In order to have quick access to DHAT Viewer from whenever I'am I decided to fork and host a GitHub Pages instance
of Valgrind's DHAT Viewer compatible with [dhat-rs](https://github.com/nnethercote/dhat-rs) minimum required version.

## License

Valgrind is licensed under the The GNU General Public License, version 2.

The valgrind/*.h headers that you may wish to include in your code (eg. valgrind.h, memcheck.h, helgrind.h, etc.)
are distributed under a BSD-style license, so you may include them in your code without worrying about license conflicts.
Some of the PThreads test cases, pth_*.c, are taken from "Pthreads Programming" by Bradford Nichols, Dick Buttlar &
Jacqueline Proulx Farrell, ISBN 1-56592-115-1, published by O'Reilly & Associates, Inc.
