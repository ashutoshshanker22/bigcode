############################################################
# <bsn.cl fy=2014 v=epl>
#
#           Copyright 2014 Big Switch Networks, Inc.
#
# Licensed under the Eclipse Public License, Version 1.0 (the
# "License"); you may not use this file except in compliance
# with the License. You may obtain a copy of the License at
#
#        http://www.eclipse.org/legal/epl-v10.html
#
# Unless required by applicable law or agreed to in writing,
# software distributed under the License is distributed on an
# "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
# either express or implied. See the License for the specific
# language governing permissions and limitations under the
# License.
#
# </bsn.cl>
############################################################

include ../../../init.mk
MODULE := cjson_util_utest
TEST_MODULE := cjson_util
DEPENDMODULES := AIM cjson IOF
GLOBAL_CFLAGS += -DAIM_CONFIG_INCLUDE_MODULES_INIT=1
GLOBAL_CFLAGS += -DAIM_CONFIG_INCLUDE_MAIN=1
GLOBAL_LINK_LIBS += -lm -lpthread
include $(BUILDER)/build-unit-test.mk
