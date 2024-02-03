# Template Unreal

Unreal 프로젝트를 위한 템플릿 저장소입니다.

`.gitignore`, `editorconfig` 와 같은 기본 설정 파일과 `Commitlint` 적용을 위한 설정 및 GitHub Workflow 파일이 포함되어 있습니다.

## 사용 방법

1. `Use this template` 으로 GitHub 저장소 생성
2. 생성된 저장소 > 설정 > Branches > Add branch protection rule
   - master
   - develop
3. git clone
4. npm i
5. 루트 폴더의 하위 폴더로 유니티 프로젝트 생성

### Branch protection rule 설정

- Require a pull request before merging
- Require status checks to pass before merging
  - Require branches to be up to date before merging
  - lint-commit 추가
- Do not allow bypassing the above settings

![image](https://github.com/Eu4ng/template-commitlint/assets/59055049/ce306e72-ac22-47c5-a558-365b6bfc14e2)

## 참고

- [template-commitlint / GitHub](https://github.com/Eu4ng/template-commitlint)
