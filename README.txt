
SVE Enhancements to LLVM
========================

This repository is a clone of the public Clang repository (http://llvm.org), plus
a single patch which provides support for the ARMv8-A Scalable Vector Extension
(SVE).

ARM is providing this repository to:
* Aid discussions about IR changes to support vectorizing loops in a scalable
  manner
* Allow partners to progress with implementation

This patch is not intended for inclusion directly into upstream LLVM. There is
a separate upstreaming effort, documented in this RFC:
http://lists.llvm.org/pipermail/llvm-dev/2018-July/124396.html

ARM provides no assurances regarding maintenance or support for this repository.
Pull requests will not be accepted.  ARM intends to remove it once upstream
LLVM has sufficiently advanced support for SVE.

This patch includes (but is not limited to):
* Minimal support for SVE -- flags plus IR interfaces


Contributors:
Alban Bridonneau
Amara Emerson
Andra-Maria Ilies
Assad Hashmi
Cullen Rhodes
David Sherwood
Florian Hahn
Francesco Petrogalli
Graham Hunter
Joshua Warburton
Kerry McLaughlin
Kiran Chandramohan
Maciej Gabka
Paul Walker
Prakhar Bahuguna
Richard Sandiford
Sander De Smalen
Will Lovett

