#
# Copyright (C) 2005, 2006, 2007, 2011 Marius L. Jøhndal
#
# This library is free software; you can redistribute it and/or
# modify it under the terms of the GNU Lesser General Public
# License as published by the Free Software Foundation; either
# version 2.1 of the License, or (at your option) any later version.
#
# This library is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
# Lesser General Public License for more details.
#
# You should have received a copy of the GNU Lesser General Public
# License along with this library; if not, write to the Free Software
# Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA
#
INCLUDES = $(GLIBS_CFLAGS) $(CURL_CFLAGS)

bin_PROGRAMS = castget

castget_SOURCES = \
  castget.c \
  channel.c \
  channel.h \
  configuration.h \
  configuration.c \
  htmlent.c \
  htmlent.h \
  libxmlutil.c \
  libxmlutil.h \
  rss.c \
  rss.h \
  urlget.c \
  urlget.h \
  utils.c \
  utils.h

castget_LDADD = \
  $(GLIBS_LIBS) \
  $(CURL_LIBS)
