# zfgrep

> 압축된 파일에서 고정 문자열을 찾습니다.
> 입력을 필요한 경우 먼저 압축 해제한 후 `grep -F`와 동일하게 작동합니다.
> 더 많은 정보: <https://manned.org/zfgrep>.

- 파일에서 정확히 일치하는 문자열 검색:

`zfgrep {{검색_문자열}} {{경로/대상/파일}}`

- 파일에서 주어진 문자열과 일치하는 줄의 수를 셈:

`zfgrep --count {{검색_문자열}} {{경로/대상/파일}}`

- 파일에서 일치하는 줄과 함께 줄 번호 표시:

`zfgrep --line-number {{검색_문자열}} {{경로/대상/파일}}`

- 검색 문자열을 포함하지 않는 모든 줄 표시:

`zfgrep --invert-match {{검색_문자열}} {{경로/대상/파일}}`

- 검색 문자열과 최소 한 번 일치하는 파일 이름만 나열:

`zfgrep --files-with-matches {{검색_문자열}} {{경로/대상/파일1 경로/대상/파일2 ...}}`
