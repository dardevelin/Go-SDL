# Copyright 2009 The Go Authors.  All rights reserved.
# Use of this source code is governed by a BSD-style
# license that can be found in the LICENSE file.

include $(GOROOT)/src/Make.inc

TARG=test
GOFILES=test.go

GC=${O}g -I../_obj
LD=${O}l -L../_obj

include $(GOROOT)/src/Make.cmd

fmt:
	gofmt -w $(wildcard *.go)
