# PEBakery 런타임 사양

## 개요

### 문서의 범위

이 문서는 PEBakery 프로그램이 실행 시간에 제공하는 환경인 PEBakery 런타임에 대한 명세를 제공한다. PEBakery 프로그램은 역사적인 이유로 특정 스크립트 프로그램들을 돌릴 수 있는 환경이 되도록 작동한다. PEBakery 런타임 사양은 이 환경의 설계에 대한 추상화된 규격이다.

PEBakery는 PEBakery 팀이 제작하고 제공하는 프로그램의 이름이지만, PEBakery 런타임 사양을 구현하는 하나의 구현체이기도 하다. 따라서 본 문서는 PEBakery 런타임 사양을 구현하는 어떤 구현체에게도 참고가 될 수 있다. 반면에 PEBakery 프로그램을 비롯해 PEBakery 런타임 사양의 구현체를 이용하는 사용자는 이 명세로부터 얻은 정보를 이용해 스크립팅에 참고할 수 있다.

PEBakery를 위한 스크립트 언어의 구체적인 문법은 [PEBakery 스크립팅 사양](/scripting-specification) 문서에서 다룬다. 본 문서는 스크립트 언어에서 참조하는 어휘들과 다른 어휘들이 이루는 의미론을 기술한다. PEBakery가 표준적으로 추구하지 않는 부분에 대해서는 [PEBakery 기행 보고](/quirks-reports) 문서에서 다룬다. PEBakery 프로그램은 실제로 본 문서에 명세된 사양과 기행 보고 문서들에서 요구된 사항을 함께 구현하도록 만들어질 것이다. 이 외에 PEBakery 프로그램의 내부 구현에 대해서는 [PEBakery 구현 내부](/implementation-internals) 문서에서 다룬다.
