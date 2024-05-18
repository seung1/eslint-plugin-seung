# eslint-plugin-seung

seung

## Installation

react-deep-dive 8.1 예제 코드를 연습한 패키지입니다.

You'll first need to install [ESLint](https://eslint.org/):

```sh
npm i eslint --save-dev
```

Next, install `eslint-plugin-seung`:

```sh
npm install eslint-plugin-seung --save-dev

yarn add -D eslint-plugin-seung
```

## Usage

Add `seung` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
  "plugins": ["seung"]
}
```

Then configure the rules you want to use under the rules section.

```json
{
  "rules": {
    "seung/no-new-date": 2
  }
}
```

0 : 규칙 비활성화

1 : 경고발생

2 : 에러로 처리

## Configurations

<!-- begin auto-generated configs list -->

TODO: Run eslint-doc-generator to generate the configs list (or delete this section if no configs are offered).

<!-- end auto-generated configs list -->

## Rules

<!-- begin auto-generated rules list -->

TODO: Run eslint-doc-generator to generate the rules list.

<!-- end auto-generated rules list -->
