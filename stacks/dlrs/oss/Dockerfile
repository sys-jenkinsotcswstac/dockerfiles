FROM clearlinux
LABEL maintainer="otc-swstacks@intel.com"

ARG swupd_args

RUN swupd update $swupd_args && \
		swupd bundle-add curl git machine-learning-tensorflow

CMD 'bash'
