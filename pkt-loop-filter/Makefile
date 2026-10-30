# SPDX-License-Identifier: (GPL-2.0 OR BSD-2-Clause)

USER_TARGETS    += pkt-loop-filter get-bond-active
BPF_TARGETS    += pkt-loop-filter.kern get-bond-active.kern
BPF_SKEL_OBJ := pkt-loop-filter.kern.o get-bond-active.kern.o
EXTRA_DEPS := pkt-loop-filter.h bond-active.h bpf-defs.h
USER_TARGETS_OBJS := bond-active.o
USER_TARGETS_OBJS_DEPS := get-bond-active.kern.skel.h

LIB_DIR = ../lib

include $(LIB_DIR)/common.mk
