 개요
===================
- 게임 타이틀: Project U
- 장르: TPS
- 플렛폼: PC
- 개발엔진: Unreal

게임소개
==================
-가상세계(Unreal)에 갇힌 주인공은 이 장소를 탈출하고자 하지만 로봇들이
주인공을 탈출하지 못하도록 저지하려 한다. 주인공은 로봇들을 처치하고
무사히 가상세계를 탈출하고자 한다. 총 3개의 웨이브로 2웨이브까지는
적들을 처치하고 3스테이지에서는 탈출을 위한 오브젝트를 먹고 탈출해야 한다.

구현
================
- AI들의 행동패턴을 Behavior Tree로 제작
- 플레이어 감지를 위한 시각Sensor AI 구현
- 각 웨이브마다 적들이 랜덤장소에서 스폰하고 난이도를 관리하는 게임 매니저 구현
- RayCast방식을 통한 무기 구현
- AimOffset기능을 구현하여 캐릭터의 총구방향이 자연스럽게 카메라 시야의 정면을 가리키도록 구현

Youtube 링크
=================
-https://youtu.be/rMg1pnqxRG4
