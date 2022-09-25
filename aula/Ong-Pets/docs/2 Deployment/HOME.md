# 2 Deployment

![diagram](https://www.plantuml.com/plantuml/svg/0/vLPHRnit37uFaF_0-ML9uDYD4Gn5d-hONPiWZesUisp0W80dqMUjEkaWwPncG_xxA9qTnwa3p2dsCCm638dcHv4VIL7lVK0NwbBlx_sWZD2r99Y7KFbttQx3kqwXmhpEQqzEM1F8X8wmPHUbKsWMkgxgxk3qUABHXElHPLTZ81zOT3kaIjlxCWAgP7r_xxB_s_XwUdjpFlrqU_dXuuUhuS5Xb4_8UMiEAc7Rq9gGznP1Q4N144W4QufMkwKn9zqwt5Nx_wR_xtBPVDUflRsoaWugBHX-fWeuG_C5UDjwjcTZWIqpWbphyA_zFU3FSpFIC2fNHSwWOwpKqT7Hx-7hssZhEgzDgE7afywRKxYSPeysjjd12iMS6DLF2vZQKc1eFHV0syxN3JlnC-0QHsN8iHKL4PDpw5ULLWnGraGZ5xX0G2CXgvmo1On-6KJnnDc5akJXF0PfAAJWeyAiDYA2KQjm3ml5QBZ8nbVTJzFf90C-eXFPNRdmq2mVjfEqv4VcRqwUi1MtE_Da7GeTUHgd1Hp3nAaItNrhBJlfYPSv6kO7CcVT8IStHqyHzvaqDi72IWmParvY_3SBrZ55yJO1HuNomILjK6PcNPdMRPYZdvC4hCESdLrI3yAHZ5lKlWqe15ShQ5lmXe9u5OEzJGPxhsImzvJ2ZFYQbBkIsFlliPW_PU-EygPRJr_PhRtlRLVsW14tbF_3TXsILWk-_O3P0Hw1J10i1rpIZk9lEjdp3-Upme80ryUyGDl3jhkojD7FGUs3BSdzw845YcrAMYX1JTGLxy_76LW7VIETLV8ny7N03OxrHuq1XaNqhyWThCp6ZOIWLQa25uElSy_nsDds-3Plgc11BFtqwTfYZ7AR3gVGjmRAhuHgCz8egUC0Y4uhVavuEmjmeuoqTpxwr4HUeXXdBmw9tB4okMMkpvfTjFZHsfYRmTpnSMqOsJ-LrWW_AqSpkravQn9zXR6VchHEObgtL4ycdAgQgkYRejReDjdL-li8vTA5PLYFbRGg7xu87ZFTJAGHVk53urmIV3BNhutU_C5Zl9adqK94fT1sWwGUQYXPjuTDaObr6f-ukmAcOz8e-4meFSmu1uclEyTbjphmOdWsU8RexG29zbU89aUibjuLh9jU9-_9I7vg_Wq0)

**Deployment diagram**

A deployment diagram allows you to illustrate how containers in the static model are mapped to infrastructure. This deployment diagram is based upon a UML deployment diagram, although simplified slightly to show the mapping between containers and deployment nodes. A deployment node is something like physical infrastructure (e.g. a physical server or device), virtualised infrastructure (e.g. IaaS, PaaS, a virtual machine), containerised infrastructure (e.g. a Docker container), an execution environment (e.g. a database server, Java EE web/application server, Microsoft IIS), etc. Deployment nodes can be nested.

**Scope**: A single software system.

**Primary elements**: Deployment nodes and containers within the software system in scope.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.