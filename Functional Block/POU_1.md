```ST
FUNCTION_BLOCK POU_1
VAR_INPUT
END_VAR 
VAR_OUTPUT
END_VAR
VAR
	start_trig : r_trig;
	stop_trig: r_trig;
	motor: BOOL;
	stop: BOOL;
	state :INT:=10;
	call_POU_2: POU_2; 
	bip_count : INT:=5;
END_VAR

FUNCTION_BLOCK POU_1 
VAR_INPUT
END_VAR 
VAR_OUTPUT
END_VAR
VAR
	start_trig : r_trig;
	stop_trig: r_trig;
	motor: BOOL;
	stop: BOOL;
	state :INT:=10;
	call_POU_2: POU_2; 
	bip_count : INT:=5;
END_VAR
```
