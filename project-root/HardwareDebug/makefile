################################################################################
# Automatically-generated file. Do not edit!
################################################################################

-include makefile.init

RM := rm -rf *.sni *.dbg *.lst *.lis *.lpp *.map *.x *.lbp *.bls *.libelf *.rel *.lbk *.abs *.mi *.jmp *.fsy 1st/*.abs 1st/*.jmp 1st/*.fsy

# All of the sources participating in the build are defined here
-include sources.mk
-include src/subdir.mk
-include src/smc_gen/r_glcdc_rx/src/subdir.mk
-include src/smc_gen/r_glcdc_rx/src/targets/rx65n/subdir.mk
-include src/smc_gen/r_pincfg/subdir.mk
-include src/smc_gen/r_bsp/mcu/all/subdir.mk
-include src/smc_gen/general/subdir.mk
-include src/smc_gen/r_bsp/board/generic_rx65n/subdir.mk
-include src/smc_gen/r_bsp/mcu/rx65n/subdir.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif 
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif 
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif 
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif 
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif 
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif 
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif 
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif 
ifneq ($(strip $(SX_DEPS)),)
-include $(SX_DEPS)
endif 
ifneq ($(strip $(JMP_DEPS)),)
-include $(JMP_DEPS)
endif 
ifneq ($(strip $(SRC_DEPS)),)
-include $(SRC_DEPS)
endif 
ifneq ($(strip $(PP_DEPS)),)
-include $(PP_DEPS)
endif 
ifneq ($(strip $(P_DEPS)),)
-include $(P_DEPS)
endif 
ifneq ($(strip $(FSY_DEPS)),)
-include $(FSY_DEPS)
endif 
endif

ifneq ($(strip $(SRC_UPPER_SRCS)),)
ALL_ASMS += $(SRC_UPPER_SRCS) 
endif
ifneq ($(strip $(SRC_SRCS)),)
ALL_ASMS += $(SRC_SRCS) 
endif
ifneq ($(strip $(S_UPPER_SRCS)),)
ALL_ASMS += $(S_UPPER_SRCS) 
endif
ifneq ($(strip $(S_SRCS)),)
ALL_ASMS += $(S_SRCS) 
endif


-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables
LINKER_OUTPUT_OUTPUTS += \
QE_for_Display_sample_RX65N_Envision.abs

LIBRARY_GENERATOR_OUTPUTTYPE_OUTPUTS += \
QE_for_Display_sample_RX65N_Envision.lib

OBJS := \
$(COMPILER_OBJS) \
$(INDIVIDUAL_COMPILER_OBJS) \
$(ASSEMBLER_OBJS) \
$(CUSTOM_OBJS)

# All Target
all: $(LINKER_OUTPUT_OUTPUTS) QE_for_Display_sample_RX65N_Envision.x

	@echo 'Build complete.'

QE_for_Display_sample_RX65N_Envision.abs: $(OBJS)  $(ALL_ASMS) $(LIBRARY_GENERATOR_OUTPUTTYPE_OUTPUTS) 
	@echo 'Invoking: Linker'
	@echo 'Building target:'
	@echo LinkerQE_for_Display_sample_RX65N_Envision.tmp=
	@sed -e "s/^/    /" "LinkerQE_for_Display_sample_RX65N_Envision.tmp"
	rlink -subcommand="LinkerQE_for_Display_sample_RX65N_Envision.tmp"
	@echo 'Finished building target:'
	@echo.


QE_for_Display_sample_RX65N_Envision.lib: 
	@echo 'Invoking: Library Generator'
	@echo LibraryGeneratorQE_for_Display_sample_RX65N_Envision.tmp=
	@sed -e "s/^/    /" "LibraryGeneratorQE_for_Display_sample_RX65N_Envision.tmp"
	lbgrx -subcommand="LibraryGeneratorQE_for_Display_sample_RX65N_Envision.tmp"
	@echo 'Finished building:'
	@echo.

QE_for_Display_sample_RX65N_Envision.x: QE_for_Display_sample_RX65N_Envision.abs
		-C:\Renesas\e2_studio\Utilities\\ccrx\renesas_cc_converter.exe QE_for_Display_sample_RX65N_Envision.abs QE_for_Display_sample_RX65N_Envision.x

# Other Targets
clean:
	-$(RM) $(LINKER_OUTPUT_OUTPUTS) $(LIBRARY_GENERATOR_OUTPUTTYPE_OUTPUTS)
	-rm -rf src/*.obj src/*.d src/*.asm src/*.p src/*.pp src/*.src src/*.jmp src/*.lst src/*.prn src/*.i 
	-rm -rf src/smc_gen/r_glcdc_rx/src/*.obj src/smc_gen/r_glcdc_rx/src/*.d src/smc_gen/r_glcdc_rx/src/*.asm src/smc_gen/r_glcdc_rx/src/*.p src/smc_gen/r_glcdc_rx/src/*.pp src/smc_gen/r_glcdc_rx/src/*.src src/smc_gen/r_glcdc_rx/src/*.jmp src/smc_gen/r_glcdc_rx/src/*.lst src/smc_gen/r_glcdc_rx/src/*.prn src/smc_gen/r_glcdc_rx/src/*.i 
	-rm -rf src/smc_gen/r_glcdc_rx/src/targets/rx65n/*.obj src/smc_gen/r_glcdc_rx/src/targets/rx65n/*.d src/smc_gen/r_glcdc_rx/src/targets/rx65n/*.asm src/smc_gen/r_glcdc_rx/src/targets/rx65n/*.p src/smc_gen/r_glcdc_rx/src/targets/rx65n/*.pp src/smc_gen/r_glcdc_rx/src/targets/rx65n/*.src src/smc_gen/r_glcdc_rx/src/targets/rx65n/*.jmp src/smc_gen/r_glcdc_rx/src/targets/rx65n/*.lst src/smc_gen/r_glcdc_rx/src/targets/rx65n/*.prn src/smc_gen/r_glcdc_rx/src/targets/rx65n/*.i 
	-rm -rf src/smc_gen/r_pincfg/*.obj src/smc_gen/r_pincfg/*.d src/smc_gen/r_pincfg/*.asm src/smc_gen/r_pincfg/*.p src/smc_gen/r_pincfg/*.pp src/smc_gen/r_pincfg/*.src src/smc_gen/r_pincfg/*.jmp src/smc_gen/r_pincfg/*.lst src/smc_gen/r_pincfg/*.prn src/smc_gen/r_pincfg/*.i 
	-rm -rf src/smc_gen/r_bsp/mcu/all/*.obj src/smc_gen/r_bsp/mcu/all/*.d src/smc_gen/r_bsp/mcu/all/*.asm src/smc_gen/r_bsp/mcu/all/*.p src/smc_gen/r_bsp/mcu/all/*.pp src/smc_gen/r_bsp/mcu/all/*.src src/smc_gen/r_bsp/mcu/all/*.jmp src/smc_gen/r_bsp/mcu/all/*.lst src/smc_gen/r_bsp/mcu/all/*.prn src/smc_gen/r_bsp/mcu/all/*.i 
	-rm -rf src/smc_gen/general/*.obj src/smc_gen/general/*.d src/smc_gen/general/*.asm src/smc_gen/general/*.p src/smc_gen/general/*.pp src/smc_gen/general/*.src src/smc_gen/general/*.jmp src/smc_gen/general/*.lst src/smc_gen/general/*.prn src/smc_gen/general/*.i 
	-rm -rf src/smc_gen/r_bsp/board/generic_rx65n/*.obj src/smc_gen/r_bsp/board/generic_rx65n/*.d src/smc_gen/r_bsp/board/generic_rx65n/*.asm src/smc_gen/r_bsp/board/generic_rx65n/*.p src/smc_gen/r_bsp/board/generic_rx65n/*.pp src/smc_gen/r_bsp/board/generic_rx65n/*.src src/smc_gen/r_bsp/board/generic_rx65n/*.jmp src/smc_gen/r_bsp/board/generic_rx65n/*.lst src/smc_gen/r_bsp/board/generic_rx65n/*.prn src/smc_gen/r_bsp/board/generic_rx65n/*.i 
	-rm -rf src/smc_gen/r_bsp/mcu/rx65n/*.obj src/smc_gen/r_bsp/mcu/rx65n/*.d src/smc_gen/r_bsp/mcu/rx65n/*.asm src/smc_gen/r_bsp/mcu/rx65n/*.p src/smc_gen/r_bsp/mcu/rx65n/*.pp src/smc_gen/r_bsp/mcu/rx65n/*.src src/smc_gen/r_bsp/mcu/rx65n/*.jmp src/smc_gen/r_bsp/mcu/rx65n/*.lst src/smc_gen/r_bsp/mcu/rx65n/*.prn src/smc_gen/r_bsp/mcu/rx65n/*.i 
	@echo
	@echo 'Clean complete.'

.PHONY: all clean 
-include ../makefile.targets