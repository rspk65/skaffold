ARG BASE
FROM golang:latest as builder
COPY web.go .
# `skaffold debug` sets SKAFFOLD_GO_GCFLAGS to disable compiler optimizations

