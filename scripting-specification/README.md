# PEBakery 스크립팅 사양

## 개요

### 문서의 범위

이 문서는 PEBakery 런타임에서 작동하도록 작성되는 스크립트 프로그램의 규격을 명세한다. PEBakery 프로그램의 환경이 PEBakery 런타임 사양의 대표적인 구현체이므로, PEBakery 프로그램에서는 이 규격에 맞는 프로그램을 작동시킬 수 있다.

PEBakery 스크립트 사양은 PEBakery 런타임 사양과는 구분되어 본 문서에서 다루어진다. 이는 스크립트 언어의 문법을 이루는 부분과 의미를 이루는 부분을 분리하여 다루기 위해서이다. [PEBakery 런타임 사양](/runtime-specification) 문서에서는 이 문서에서 참조하는 개별 어휘가 다른 어휘들과의 관계에서 갖는 의미에 대해 구체적으로 서술한다.

PEBakery 스크립트 사양을 이용해 PEBakery 프로그램에 맞는 스크립트 프로그램을 직접 작성하고 작동시키고 싶은 사용자를 위한 도움말은 [PEBakery 사용자 매뉴얼](/user-manual) 문서에 정리된다. PEBakery 프로그램이 PEBakery 스크립트 사양을 어떻게 구현하고 있는지는 [PEBakery 구현 내부](/implementation-internals) 문서에서 다룬다.
