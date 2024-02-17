cmake_minimum_required(VERSION 3.28)
project(objchoice)

set(CMAKE_CXX_STANDARD 17)

add_executable(objchoice main.cpp
        develop/tools/task.cpp
        develop/tools/task.h
        develop/tools/gtk/widget.cpp
        develop/tools/gtk/widget.h
        develop/tools/gtk/provider.cpp
        develop/tools/gtk/provider.h
        develop/tools/gtk/thread.cpp
        develop/tools/gtk/thread.h
        develop/tools/gtk/lapturway.cpp
        develop/tools/gtk/lapturway.h
        develop/tools/gtk/gboolean.cpp
        develop/tools/gtk/gboolean.h
        develop/tools/defts/uiprovider.cpp
        develop/tools/defts/uiprovider.h
        develop/tools/defts/uiproviderint.cpp
        develop/tools/defts/uiproviderint.h
        develop/tools/defts/agsuiprovider.cpp
        develop/tools/defts/agsuiprovider.h
        develop/tools/defts/uiproviderget.cpp
        develop/tools/defts/uiproviderget.h
        develop/tools/defts/uiproviderset.cpp
        develop/tools/defts/uiproviderset.h
        develop/tools/gettype/myas.cpp
        develop/tools/gettype/myas.h
        develop/tools/types/and/values.cpp
        develop/tools/types/and/values.h
        develop/tools/object/hierarchy/ginterface.cpp
        develop/tools/object/hierarchy/ginterface.h
        develop/tools/known/implementations/includes.cpp
        develop/tools/known/implementations/includes.h
        develop/tools/description/ui/headers.cpp
        develop/tools/description/ui/headers.h
        develop/tools/functions/getwindow/gtkwidget.cpp
        develop/tools/functions/getwindow/gtkwidget.h
        develop/tools/parameters/ui_provider/mazapool/agsuiprovider.cpp
        develop/tools/parameters/ui_provider/mazapool/agsuiprovider.h
        develop/tools/parameters/windows/agswindow.cpp
        develop/tools/parameters/windows/agswindow.h
        develop/tools/parameters/ui_provider/lapslink/ui/myaslink.cpp
        develop/tools/parameters/ui_provider/lapslink/ui/myaslink.h
        develop/tools/parameters/ui_provider/lapslink/ui/getui.cpp
        develop/tools/parameters/ui_provider/lapslink/ui/getui.h
        develop/tools/parameters/ui_provider/lapslink/ui/setui.cpp
        develop/tools/parameters/ui_provider/lapslink/ui/setui.h)
