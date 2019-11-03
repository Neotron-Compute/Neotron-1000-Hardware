################################################################################
# Automatically-generated file. Do not edit!
################################################################################

-include ../makefile.init

RM := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
-include Drivers/STM32H7xx_HAL_Driver/Src/subdir.mk
-include Core/Startup/subdir.mk
-include Core/Src/subdir.mk
-include subdir.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXECUTABLES += \
Neotron_2400HX.elf \

SIZE_OUTPUT += \
default.size.stdout \

OBJDUMP_LIST += \
Neotron_2400HX.list \


# All Target
all: Neotron_2400HX.elf secondary-outputs

# Tool invocations
Neotron_2400HX.elf: $(OBJS) $(USER_OBJS) /home/lauren/STM32CubeIDE/workspace_1.1.0/Neotron_2400HX/STM32H743ZITX_FLASH.ld
	arm-none-eabi-gcc -o "Neotron_2400HX.elf" @"objects.list" $(USER_OBJS) $(LIBS) -mcpu=cortex-m7 -T"/home/lauren/STM32CubeIDE/workspace_1.1.0/Neotron_2400HX/STM32H743ZITX_FLASH.ld" --specs=nosys.specs -Wl,-Map="Neotron_2400HX.map" -Wl,--gc-sections -static --specs=nano.specs -mfpu=fpv5-d16 -mfloat-abi=hard -mthumb -Wl,--start-group -lc -lm -Wl,--end-group
	@echo 'Finished building target: $@'
	@echo ' '

default.size.stdout: $(EXECUTABLES)
	arm-none-eabi-size  $(EXECUTABLES)
	@echo 'Finished building: $@'
	@echo ' '

Neotron_2400HX.list: $(EXECUTABLES)
	arm-none-eabi-objdump -h -S $(EXECUTABLES) > "Neotron_2400HX.list"
	@echo 'Finished building: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) *
	-@echo ' '

secondary-outputs: $(SIZE_OUTPUT) $(OBJDUMP_LIST)

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets
