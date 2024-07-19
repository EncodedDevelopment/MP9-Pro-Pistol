# MP9-Pro-Pistol
Custom addon (Animated) Pistol with suppressor attachments


copy and paste into ox_inventory/data/weapons.lua


		['WEAPON_MP9PRO'] = {
			label = 'MP9 Pro',
			weight = 1180,
			durability = 0.03,
			ammoname = 'ammo-9',
			description = '9 mm Pistol Gun For Encoded',
		},

this must be under components in weapons.lua

	['w_pi_mp9pro_supp'] = {
		label = 'MP9 Pro Suppressor',
		type = 'scope',
		weight = 480,
		description = "Suppressor for MP9 Pro",
		client = {
			component = {`COMPONENT_AT_MP9PRO_SUPP`},
			usetime = 2500
		}
	},
