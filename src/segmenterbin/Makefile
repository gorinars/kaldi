
all:

EXTRA_CXXFLAGS = -Wno-sign-compare
include ../kaldi.mk


CXXFLAGS += -std=c++0x

BINFILES = segmentation-init-from-ali gmm-update-segmentation segmentation-to-rttm

OBJFILES =



TESTFILES = 

ADDLIBS = ../hmm/kaldi-hmm.a ../gmm/kaldi-gmm.a  ../segmenter/kaldi-segmenter.a ../tree/kaldi-tree.a \
					../util/kaldi-util.a ../matrix/kaldi-matrix.a ../base/kaldi-base.a ../thread/kaldi-thread.a

include ../makefiles/default_rules.mk

