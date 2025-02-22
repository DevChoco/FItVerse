# PJ : FItVerse
> - FIt_Verse_App
> - 사용자의 신체에 맞춘 옷(Fit)과 가상 세계(Universe)를 합쳐, 개개인의 맞춤 패션 경험을 제공하는 의미
> - 목표 : 사용자의 퍼스널컬러, 체형 등의 데이터를 분석해 알맞은 옷을 추천해주고 해당 옷의 예상 착용 사진도 제공
-------
# 연구목표 정리

## 1. 연구 개요
현재 키워드 추출 AI(API 활용)를 통해 장면에 어울리는 텍스트 도출까지는 완료된 상태입니다.  
이를 기반으로 **해당 키워드에 적합한 이미지(또는 영상)를 영상에 합성하는 기술**을 개발하고자 합니다.

## 2. 연구 목표
1. **지정된 영역 내 물체 합성**  
   - 주어진 사진(씬)에서 특정 영역을 설정하고, 해당 영역에 주어진 물체를 자연스럽게 합성  
   - 주어진 영상(씬)에서도 동일한 방식으로 합성 (관련 OPENAPI 존재 가능성 있음)  

2. **영역 미지정 시 물체 합성**  
   - 특정 영역을 설정하지 않고 주어진 물체를 자연스럽게 합성  
   - 또는, 특정 영역을 설정한 후 임의의 물체 리스트에서 적절한 물체를 선별하여 합성  

3. **스토리 기반 장면 추천 및 합성**  
   - 영상의 흐름(분위기)을 분석하여 제품과 어울리는 장면을 추천  
   - 해당 장면에 적절한 물체를 합성  

## 3. 최종 목표
🎯 **"영상 또는 단일 이미지에 어울리는 물건을 자동 삽입하는 기술 개발"**  
- 영상 내 태그 정보를 기반으로 적절한 단어(키워드)를 도출  
- 해당 단어에 어울리는 물체를 찾아 자동으로 영상에 삽입  

## 4. 추가 요청 사항
- 현재 정리된 방식이 최적이 아닐 수도 있으며, 더 나은 방법이 있다면 제안 가능  
- 기술 개발을 위해 필요한 자료가 있다면 빠르게 준비하여 제공 예정
-------
> ## Flutter Docs
>This project is a starting point for a Flutter application.
>
>A few resources to get you started if this is your first Flutter project:
>
> - [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
> - [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)
>
> For help getting started with Flutter development, view the
> [online documentation](https://docs.flutter.dev/), which offers tutorials,
> samples, guidance on mobile development, and a full API reference.
