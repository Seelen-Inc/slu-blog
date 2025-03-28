# **Seelen UI : 설치 방법 및 채널 업데이트**

## **설치 옵션**

### **Microsoft Store (MSIX)**

Microsoft Store에서 최신 버전을 다운로드하십시오. 이것은 가장 안전합니다
 자동 업데이트와 함께 사용자 친화적 인 옵션.

*   장점 :
    *   자동 업데이트.
    *   Microsoft가 확인하고 승인했습니다.
    *   높은 보안 및 신뢰성.
    *   이 버전은 .exe 설치 프로그램보다 Lightweighter 버전입니다
         디버그 기호가 포함되어 있습니다.
*   단점 :
    *   업데이트는 승인하는 데 1-3 일이 소요될 수 있습니다.
    *   디버깅 및 보고서 문제가 더 어렵습니다.

***

### **Winget (MSIX)**

다음 명령을 사용하여 최신 버전을 설치하십시오.

```pwsh
winget install --id Seelen.SeelenUI
```

빠른 설치를 통해 Microsoft Store의 동일한 장단점
 명령 줄.

***

### \*\*. exe 설치 프로그램 \*\*

릴리스 페이지에서 Setup.exe 설치 프로그램을 다운로드하여 실행하십시오.

*   장점 :
    *   즉각적인 업데이트로 더 빠른 설치.
    *   새로운 릴리스에 대한 알림을받을 수있는 즉시 알림을받습니다.
*   단점 :
    *   디지털로 서명하지 않으므로 안티 바이러스 경고를 유발할 수 있습니다.
    *   이 버전에는 디버그가 포함되어 있기 때문에 MSIX 설치 프로그램보다 가벼운
         기호.

## **채널 업데이트**

> 업데이트 채널의 IndenPendent 모든 버전은 자동 업데이트를 받고
>  또한 불안정한 업데이트 채널을 사용하는 경우
>  보다 안정적인 업데이트 채널, 예 : 야간마다 업데이트가 나이트이지만
>  또한 베타 및 릴리스에서

### **릴리스 (안정)**

모든 사용자에게 가장 안전하고 권장되는 채널입니다.

*   특징:
    *   중요한 버그없이 철저히 테스트했습니다.
    *   생산 및 일상적인 사용에 이상적입니다.
    *   Microsoft Store, Winget, .msix 및 .exe에서 사용할 수 있습니다.

### **베타**

공식적으로 출시되기 전에 새로운 기능을 시도하려는 사용자를 대상으로합니다.
 이 채널에는 베타 및 릴리스 후보가 포함됩니다.

*   특징:
    *   테스트중인 새로운 기능이 포함되어 있습니다.
    *   사소한 버그가있을 수 있습니다.
    *   안정적인 릴리스보다 더 빈번한 업데이트.
    *   릴리스 페이지에서 .exe 만 사용할 수 있습니다.

### **야간**

최신 변경 사항에 액세스하려는 고급 사용자 및 개발자를 위해
 실험적인 특징.

*   특징:
    *   가장 최근의 변경 사항이 포함되어 있지만 철저히 테스트되지는 않았습니다.
    *   버그 또는 미완성 기능이 포함될 수 있습니다.
    *   매일 또는 모든 중요한 코드 변경으로 업데이트되었습니다.
    *   릴리스 페이지에서 .exe 만 사용할 수 있습니다.

on에 대해 자세히 알아보십시오 [Seelen ui nighly](./nightly.md)

## **setup.exe vs msix에서 업데이트를 받으십시오**

MSIX 업데이트는 Microsoft Store에서 관리하지만 setup.exe에서는
 응용 프로그램에 업데이트가 포함되어 있습니다.
 업데이트를 사용할 수있는 경우 알림.

![Seelen UI update notification on settings window](https://github.com/Seelen-Inc/slu-blog/blob/master/blog/seelen-ui-distribution-channels/image.png?raw=true)

알림을 클릭하면 다운로드 및 설치가 시작됩니다.
 업데이트는 응용 프로그램을 자동으로 다시 시작합니다.
