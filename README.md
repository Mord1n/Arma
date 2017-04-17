Radar.sqf

 * Replace old file with new: core\cop\fn_radar.sqf
 * Add this to fn_keyHandler:
// Case 181 is the "/" key beside numlock.
case 181:
{
	if (!_alt && !_ctrlKey && playerSide == west) then
	{
		[] call life_fnc_radar;
	};
}; 
