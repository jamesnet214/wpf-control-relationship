<div align=center>
  <h2>WPF Control Relationship</h2>
  <br/>
 
  이 레포지토리는 DevNcore팀이 관리하고 있습니다.
  <br />
  <a href="https://github.com/devncore/devncore"><strong>더 알아보기 »</strong></a>
 
  <br />
  <br />
 
  <p align="center">
   <a href="https://github.com/devncore/wpf-control-relationship/stargazers"><img src="https://img.shields.io/github/stars/devncore/wpf-control-relationship" alt="Github Stars"></a>
   <img src="https://img.shields.io/github/license/devncore/wpf-control-relationship" alt="License">
   <a href="https://github.com/devncore/wpf-control-relationship/pulse"><img src="https://img.shields.io/github/commit-activity/m/devncore/wpf-control-relationship" alt="Commits-per-month"></a>
 </p>
</div>

<br />
  
## 상속관계도
![image](https://user-images.githubusercontent.com/68521148/134800050-a19b73b1-db8a-485a-916a-98be327abe8f.PNG)

<br />

## DispatcherObject
```namespace
System.Threading.DispatcherObject
```
> DispatcherObject는 Dispatcher를 갖고 있는 클래스입니다.    
> Dispatcher는 쓰레드에 대해서 관리를 하는 역할을 하고 있습니다.    
> 즉 하나의 Object에 대해서 단독으로 실행되는 작업을 관리하는 기능을 하고 있습니다.    

### 주요 속성
System.Windows.Threading.Dispatcher Dispatcher

<br />

## DependencyObject
```namespace
System.Windows.DependencyObject
```
> WPF에서는 속성 값을 이용해서 다양한 기능을 구현할 수 있습니다.    
> DependencyObject는 속성 값을 관리할 수 있는 기능을 제공하는 클래스입니다.    
<br />

## Visual
```namespace
System.Windows.Media.Visual
```
> 시스템이 정의된 후 화면에서 픽셀을 그립니다.    
> Visual는 시각적 개체 트리를 빌드 하기 위해    
> 각각 선택적인 포함 그리기 명령과 해당 명령을 렌더링 하는 방법에 대한 메타데이터를 제공합니다.    


<br />

## UIElement
```namespace
System.Windows.UIElement
```
> UIElement는 레이아웃, 입력 및 이벤트를 비롯한 핵심 하위 시스템을 정의합니다.    
> 레이아웃은 WPF의 핵심 개념입니다.    

### 주요 메서드
OnPreviewMouseDown(MouseButtonEventArgs)    

> 버블링과 터널링에 의해 동작하는 이벤트들이 모두 UIElement 클래스에 포함되어 있습니다.

<br />

## FrameworkElement
```namespace
System.Windows.FrameworkElement
```

- UIElment에 의해 도입된 기본 레이아웃 계약을 기반으로 하며 레이아웃 제작자가 속성 중심 레이아웃 의미 체계 집합의 일관성을 보다 쉽게 유지할 수 있도록 레이아웃 "슬롯" 게념을 추가합니다.    
- HorizontalAlignment, Margin 등의 속성은 레이아웃 컨테이너 내의 일관된 동작을 FrameworkElement에서 파생된 모든 구성 요소에 제공합니다.    
- FrameworkElement는 보다 쉬운 API 노출을 WPF의 핵심 계층에 있는 여러 기능에 제공합니다.


### 주요 프로퍼티
- `object` DataContext  
- `bool` IsHitTestVisible
 
<br />

## Control
```namespace
System.Windows.Controls.Control
```

<br />

### 주요 프로퍼티
- System.Windows.Media.Brush Background

<br />
