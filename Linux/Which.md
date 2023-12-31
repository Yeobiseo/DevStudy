## Which
##### 'which'는 Linux와 Unix 기반 시스템에서 사용되는 명령어 중 하나로, 실행 파일의 경로를 찾아주는 유틸리티입니다. 주어진 명령어가 시스템에서 어느 디렉토리에 위치하는지 확인하는데 사용됩니다. 'which' 명령어는 해당 명령어를 찾으면 해당 경로를 출력하고, 명령어를 찾지 못하면 아무런 출력을 하지 않습니다.
<pre>
which [옵션] 명령어
</pre>
___
#### 주요 옵션들

`-a`, `--all`
- 여러 경로에서 명령어를 찾을 경우 모든 경로를 출력합니다.
- 즉, 같은 이름의 명령어가 여러 디렉토리에 있는 경우에 사용됩니다.

`-i`, `--read-alias`
- 명령어가 별칭(alias)로 설정되어 있을 경우, 별칭 이름을 출력합니다.

`-p`, `--show-tilde`
- 출력할 때, 홈 디렉토리를 '~'으로 표시합니다.
