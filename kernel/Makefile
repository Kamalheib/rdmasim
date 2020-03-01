LINUX_SRC_PATH = /lib/modules/$(shell uname -r)/build

default: modules

modules:
	@${MAKE} -C $(LINUX_SRC_PATH) M=`pwd` modules

all:
	@${MAKE} -C $(LINUX_SRC_PATH) M=`pwd` modules

clean:
	@${MAKE} -C $(LINUX_SRC_PATH) M=`pwd` clean

.PHONY: clean modules install
