##### 生成go语言bin方法，在对应的gopath的src下执行下方代码

**前提：已经安装go**

`go install github.com/uudashr/gopkgs/cmd/gopkgs \
 && go install github.com/ramya-rao-a/go-outline \ 
 && go install github.com/acroca/go-symbols \ 
 && go install golang.org/x/tools/cmd/guru \ 
 && go install golang.org/x/tools/cmd/gorename \ 
 && go install github.com/golang/lint/golint \ 
 && go install github.com/sqs/goreturns \ 
 && go install github.com/derekparker/delve \ 
 && go install github.com/derekparker/delve/cmd/dlv`
