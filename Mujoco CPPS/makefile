COMMON=/O2 /MT /EHsc /arch:AVX /I../include /Fe../bin/

all:
	cl $(COMMON) testxml.cpp                 ../bin/mujoco200nogl.lib
	cl $(COMMON) testspeed.cpp               ../bin/mujoco200nogl.lib
	cl $(COMMON) compile.cpp                 ../bin/mujoco200nogl.lib
	cl $(COMMON) derivative.cpp /openmp      ../bin/mujoco200nogl.lib
	cl $(COMMON) basic.cpp ../bin/glfw3.lib  ../bin/mujoco200.lib
	cl $(COMMON) record.cpp ../bin/glfw3.lib ../bin/mujoco200.lib
	cl $(COMMON) simulate.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
	cl $(COMMON) palm_plane.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
	cl $(COMMON) palm_bottle.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
	cl $(COMMON) palm_sdriver.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_dumbell.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_drill.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_flask.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_hammer.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_knife.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_pinscrew.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_plier.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_ratchet.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_ratchet2.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_shovel.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_blender.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_broom.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_comb.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_stool.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_spray.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_wiper.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_tap.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_safe.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_spatula.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_dustbin.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_hammer2.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_kettle.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_pframe.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_spoon.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_turner.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_scraper.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_plate.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_bunny.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_lemon.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_pan.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_door.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_mug.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_lever.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_switch.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_jack.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_box.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_ball.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_tap2.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_needle.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_oven.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_drawer.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_case.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
        cl $(COMMON) palm_tap3.cpp ../include/uitools.c ../bin/glfw3.lib ../bin/mujoco200.lib
	del *.obj
