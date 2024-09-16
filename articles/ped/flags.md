# Ped Config Flags

Ped config flags are flags that configure behaviour or show states of peds.
Flag means: that the value of the variable can only be 0 or 1 (false or true). The flags can be read with <a href="https://natives.altv.mp/#/0x7EE53118C892B513" target="_blank">getPedConfigFlag</a> and written with <a href="https://natives.altv.mp/#/0x1913FE4CBF41C463" target="_blank">setPedConfigFlag</a>.

| Name | Flag ID |
| ---- | ------- |
| PED_FLAG_CREATED_BY_FACTORY | 0 |
| PED_FLAG_CAN_BE_SHOT_IN_VEHICLE | 1 |
| PED_FLAG_NO_CRITICAL_HITS | 2 |
| PED_FLAG_DROWNS_IN_WATER | 3 |
| PED_FLAG_DROWNS_IN_SINKING_VEHICLE | 4 |
| PED_FLAG_DIES_INSTANTLY_WHEN_SWIMMING | 5 |
| PED_FLAG_HAS_BULLET_PROOF_VEST | 6 |
| PED_FLAG_UPPER_BODY_DAMAGE_ANIMS_ONLY | 7 |
| PED_FLAG_NEVER_FALL_OFF_SKIS | 8 |
| PED_FLAG_NEVER_EVER_TARGET_THIS_PED | 9 |
| PED_FLAG_THIS_PED_IS_A_TARGET_PRIORITY | 10 |
| PED_FLAG_TARGETTABLE_WITH_NO_LOS | 11 |
| PED_FLAG_DOESNT_LISTEN_TO_PLAYER_GROUP_COMMANDS | 12 |
| PED_FLAG_NEVER_LEAVES_GROUP | 13 |
| PED_FLAG_DOESNT_DROP_WEAPONS_WHEN_DEAD | 14 |
| PED_FLAG_SET_DELAYED_WEAPON_AS_CURRENT | 15 |
| PED_FLAG_KEEP_TASKS_AFTER_CLEAN_UP | 16 |
| PED_FLAG_BLOCK_NON_TEMPORARY_EVENTS | 17 |
| PED_FLAG_HAS_A_SCRIPT_BRAIN | 18 |
| PED_FLAG_WAITING_FOR_SCRIPT_BRAIN_TO_LOAD | 19 |
| PED_FLAG_ALLOW_MEDICS_TO_REVIVE_ME | 20 |
| PED_FLAG_MONEY_HAS_BEEN_GIVEN_BY_SCRIPT | 21 |
| PED_FLAG_NOT_ALLOWED_TO_CROUCH | 22 |
| PED_FLAG_DEATH_PICKUPS_PERSIST | 23 |
| PED_FLAG_IGNORE_SEEN_MELEE | 24 |
| PED_FLAG_FORCE_DIE_IF_INJURED | 25 |
| PED_FLAG_DONT_DRAG_ME_OUT_CAR | 26 |
| PED_FLAG_STAY_IN_CAR_ON_JACK | 27 |
| PED_FLAG_FORCE_DIE_IN_CAR | 28 |
| PED_FLAG_GET_OUT_UNDRIVEABLE_VEHICLE | 29 |
| PED_FLAG_WILL_REMAIN_ON_BOAT_AFTER_MISSION_ENDS | 30 |
| PED_FLAG_DONT_STORE_AS_PERSISTENT | 31 |
| PED_FLAG_WILL_FLY_THROUGH_WINDSCREEN | 32 |
| PED_FLAG_DIE_WHEN_RAGDOLL | 33 |
| PED_FLAG_HAS_HELMET | 34 |
| PED_FLAG_USE_HELMET | 35 |
| PED_FLAG_DONT_TAKE_OFF_HELMET | 36 |
| PED_FLAG_HIDE_IN_CUTSCENE | 37 |
| PED_FLAG_PED_IS_ENEMY_TO_PLAYER | 38 |
| PED_FLAG_DISABLE_EVASIVE_DIVES | 39 |
| PED_FLAG_PED_GENERATES_DEAD_BODY_EVENTS | 40 |
| PED_FLAG_DONT_ATTACK_PLAYER_WITHOUT_WANTED_LEVEL | 41 |
| PED_FLAG_DONT_INFLUENCE_WANTED_LEVEL | 42 |
| PED_FLAG_DISABLE_PLAYER_LOCKON | 43 |
| PED_FLAG_DISABLE_LOCKON_TO_RANDOM_PEDS | 44 |
| PED_FLAG_ALLOW_LOCKON_TO_FRIENDLY_PLAYERS | 45 |
| PED_FLAG_DISABLE_HORN_AUDIO_WHEN_DEAD  | 46 |
| PED_FLAG_PED_BEING_DELETED | 47 |
| PED_FLAG_BLOCK_WEAPON_SWITCHING | 48 |
| PED_FLAG_BLOCK_GROUP_PED_AIMED_AT_RESPONSE | 49 |
| PED_FLAG_WILL_FOLLOW_LEADER_ANY_MEANS | 50 |
| PED_FLAG_BLIPPED_BY_SCRIPT | 51 |
| PED_FLAG_DRAW_RADAR_VISUAL_FIELD | 52 |
| PED_FLAG_STOP_WEAPON_FIRING_ON_IMPACT | 53 |
| PED_FLAG_DISSABLE_AUTO_FALL_OFF_TESTS | 54 |
| PED_FLAG_STEER_AROUND_DEAD_BODIES | 55 |
| PED_FLAG_CONSTRAIN_TO_NAV_MESH | 56 |
| PED_FLAG_SYNCING_ANIMATED_PROPS | 57 |
| PED_FLAG_IS_FIRING | 58 |
| PED_FLAG_WAS_FIRING | 59 |
| PED_FLAG_IS_STANDING | 60 |
| PED_FLAG_WAS_STANDING | 61 |
| PED_FLAG_IN_VEHICLE | 62 |
| PED_FLAG_ON_MOUNT | 63 |
| PED_FLAG_ATTACHED_TO_VEHICLE | 64 |
| PED_FLAG_IS_SWIMMING | 65 |
| PED_FLAG_WAS_SWIMMING | 66 |
| PED_FLAG_IS_SKIING | 67 |
| PED_FLAG_IS_SITTING | 68 |
| PED_FLAG_KILLED_BY_STEALTH | 69 |
| PED_FLAG_KILLED_BY_TAKEDOWN | 70 |
| PED_FLAG_KNOCKEDOUT | 71 |
| PED_FLAG_CLEAR_RADAR_BLIP_ON_DEATH | 72 |
| PED_FLAG_JUST_GOT_OFF_TRAIN | 73 |
| PED_FLAG_JUST_GOT_ON_TRAIN | 74 |
| PED_FLAG_USING_COVER_POINT | 75 |
| PED_FLAG_IS_IN_THE_AIR | 76 |
| PED_FLAG_KNOCKED_UP_INTO_AIR | 77 |
| PED_FLAG_IS_AIMING_GUN | 78 |
| PED_FLAG_HAS_JUST_LEFT_CAR | 79 |
| PED_FLAG_TARGET_WHEN_INJURED_ALLOWED | 80 |
| PED_FLAG_CURR_LEFT_FOOT_COLL_N_M | 81 |
| PED_FLAG_PREV_LEFT_FOOT_COLL_N_M | 82 |
| PED_FLAG_CURR_RIGHT_FOOT_COLL_N_M | 83 |
| PED_FLAG_PREV_RIGHT_FOOT_COLL_N_M | 84 |
| PED_FLAG_HAS_BEEN_BUMPED_IN_CAR | 85 |
| PED_FLAG_IN_WATER_TASK_QUIT_TO_CLIMB_LADDER | 86 |
| PED_FLAG_N_M_TWO_HANDED_WEAPON_BOTH_HANDS_CONSTRAINED | 87 |
| PED_FLAG_CREATED_BLOOD_POOL_TIMER | 88 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FROM_ANY_PED_IMPACT | 89 |
| PED_FLAG_GROUP_PED_FAILED_TO_ENTER_COVER | 90 |
| PED_FLAG_ALREADY_CHATTED_ON_PHONE | 91 |
| PED_FLAG_ALREADY_REACTED_TO_PED_ON_ROOF | 92 |
| PED_FLAG_FORCE_PED_LOAD_COVER | 93 |
| PED_FLAG_BLOCK_COWERING_IN_COVER | 94 |
| PED_FLAG_BLOCK_PEEKING_IN_COVER | 95 |
| PED_FLAG_JUST_LEFT_CAR_NOT_CHECKED_FOR_DOORS | 96 |
| PED_FLAG_VAULT_FROM_COVER | 97 |
| PED_FLAG_AUTO_CONVERSATION_LOOK_ATS | 98 |
| PED_FLAG_USING_CROUCHED_PED_CAPSULE | 99 |
| PED_FLAG_HAS_DEAD_PED_BEEN_REPORTED | 100 |
| PED_FLAG_FORCED_AIM | 101 |
| PED_FLAG_STEERS_AROUND_PEDS | 102 |
| PED_FLAG_STEERS_AROUND_OBJECTS | 103 |
| PED_FLAG_OPEN_DOOR_ARM_I_K | 104 |
| PED_FLAG_FORCE_RELOAD | 105 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FROM_VEHICLE_IMPACT | 106 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FROM_BULLET_IMPACT | 107 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FROM_EXPLOSIONS | 108 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FROM_FIRE | 109 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FROM_ELECTROCUTION | 110 |
| PED_FLAG_IS_BEING_DRAGGED_TO_SAFETY | 111 |
| PED_FLAG_HAS_BEEN_DRAGGED_TO_SAFETY | 112 |
| PED_FLAG_KEEP_WEAPON_HOLSTERED_UNLESS_FIRED | 113 |
| PED_FLAG_FORCE_SCRIPT_CONTROLLED_KNOCKOUT | 114 |
| PED_FLAG_FALL_OUT_OF_VEHICLE_WHEN_KILLED | 115 |
| PED_FLAG_GET_OUT_BURNING_VEHICLE | 116 |
| PED_FLAG_BUMPED_BY_PLAYER | 117 |
| PED_FLAG_RUN_FROM_FIRES_AND_EXPLOSIONS | 118 |
| PED_FLAG_TREAT_AS_PLAYER_DURING_TARGETING | 119 |
| PED_FLAG_IS_HAND_CUFFED | 120 |
| PED_FLAG_IS_ANKLE_CUFFED | 121 |
| PED_FLAG_DISABLE_MELEE | 122 |
| PED_FLAG_DISABLE_UNARMED_DRIVEBYS | 123 |
| PED_FLAG_JUST_GETS_PULLED_OUT_WHEN_ELECTROCUTED | 124 |
| PED_FLAG_UNUSED_1 | 125 |
| PED_FLAG_WILL_NOT_HOTWIRE_LAW_ENFORCEMENT_VEHICLE | 126 |
| PED_FLAG_WILL_COMMANDEER_RATHER_THAN_JACK | 127 |
| PED_FLAG_CAN_BE_AGITATED | 128 |
| PED_FLAG_FORCE_PED_TO_FACE_LEFT_IN_COVER | 129 |
| PED_FLAG_FORCE_PED_TO_FACE_RIGHT_IN_COVER | 130 |
| PED_FLAG_BLOCK_PED_FROM_TURNING_IN_COVER | 131 |
| PED_FLAG_KEEP_RELATIONSHIP_GROUP_AFTER_CLEAN_UP | 132 |
| PED_FLAG_FORCE_PED_TO_BE_DRAGGED | 133 |
| PED_FLAG_PREVENT_PED_FROM_REACTING_TO_BEING_JACKED | 134 |
| PED_FLAG_IS_SCUBA | 135 |
| PED_FLAG_WILL_ARREST_RATHER_THAN_JACK | 136 |
| PED_FLAG_REMOVE_DEAD_EXTRA_FAR_AWAY | 137 |
| PED_FLAG_RIDING_TRAIN | 138 |
| PED_FLAG_ARREST_RESULT | 139 |
| PED_FLAG_CAN_ATTACK_FRIENDLY | 140 |
| PED_FLAG_WILL_JACK_ANY_PLAYER | 141 |
| PED_FLAG_BUMPED_BY_PLAYER_VEHICLE | 142 |
| PED_FLAG_DODGED_PLAYER_VEHICLE | 143 |
| PED_FLAG_WILL_JACK_WANTED_PLAYERS_RATHER_THAN_STEAL_CAR | 144 |
| PED_FLAG_NO_COP_WANTED_AGGRO | 145 |
| PED_FLAG_DISABLE_LADDER_CLIMBING | 146 |
| PED_FLAG_STAIRS_DETECTED | 147 |
| PED_FLAG_SLOPE_DETECTED | 148 |
| PED_FLAG_HELMET_HAS_BEEN_SHOT | 149 |
| PED_FLAG_COWER_INSTEAD_OF_FLEE | 150 |
| PED_FLAG_CAN_ACTIVATE_RAGDOLL_WHEN_VEHICLE_UPSIDE_DOWN | 151 |
| PED_FLAG_ALWAYS_RESPOND_TO_CRIES_FOR_HELP | 152 |
| PED_FLAG_DISABLE_BLOOD_POOL_CREATION | 153 |
| PED_FLAG_SHOULD_FIX_IF_NO_COLLISION | 154 |
| PED_FLAG_CAN_PERFORM_ARREST | 155 |
| PED_FLAG_CAN_PERFORM_UNCUFF | 156 |
| PED_FLAG_CAN_BE_ARRESTED | 157 |
| PED_FLAG_MOVER_CONSTRICTED_BY_OPPOSING_COLLISIONS | 158 |
| PED_FLAG_PLAYER_PREFER_FRONT_SEAT_M_P | 159 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FROM_IMPACT_OBJECT | 160 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FROM_MELEE | 161 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FROM_WATER_JET | 162 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FROM_DROWNING | 163 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FROM_FALLING | 164 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FROM_RUBBER_BULLET | 165 |
| PED_FLAG_IS_INJURED | 166 |
| PED_FLAG_DONT_ENTER_VEHICLES_IN_PLAYERS_GROUP | 167 |
| PED_FLAG_SWIMMING_TASKS_RUNNING | 168 |
| PED_FLAG_PREVENT_ALL_MELEE_TAUNTS | 169 |
| PED_FLAG_FORCE_DIRECT_ENTRY | 170 |
| PED_FLAG_ALWAYS_SEE_APPROACHING_VEHICLES | 171 |
| PED_FLAG_CAN_DIVE_AWAY_FROM_APPROACHING_VEHICLES | 172 |
| PED_FLAG_ALLOW_PLAYER_TO_INTERRUPT_VEHICLE_ENTRY_EXIT | 173 |
| PED_FLAG_ONLY_ATTACK_LAW_IF_PLAYER_IS_WANTED | 174 |
| PED_FLAG_PLAYER_IN_CONTACT_WITH_KINEMATIC_PED | 175 |
| PED_FLAG_PLAYER_IN_CONTACT_WITH_SOMETHING_OTHER_THAN_KINEMATIC_PED | 176 |
| PED_FLAG_PEDS_JACKING_ME_DONT_GET_IN | 177 |
| PED_FLAG_ADDITIONAL_RAPPELLING_PED | 178 |
| PED_FLAG_PED_IGNORES_ANIM_INTERRUPT_EVENTS | 179 |
| PED_FLAG_IS_IN_CUSTODY | 180 |
| PED_FLAG_FORCE_STANDARD_BUMP_REACTION_THRESHOLDS | 181 |
| PED_FLAG_LAW_WILL_ONLY_ATTACK_IF_PLAYER_IS_WANTED | 182 |
| PED_FLAG_IS_AGITATED | 183 |
| PED_FLAG_PREVENT_AUTO_SHUFFLE_TO_DRIVERS_SEAT | 184 |
| PED_FLAG_USE_KINEMATIC_MODE_WHEN_STATIONARY | 185 |
| PED_FLAG_ENABLE_WEAPON_BLOCKING | 186 |
| PED_FLAG_HAS_HURT_STARTED | 187 |
| PED_FLAG_DISABLE_HURT | 188 |
| PED_FLAG_PLAYER_IS_WEIRD | 189 |
| PED_FLAG_PED_HAD_PHONE_CONVERSATION | 190 |
| PED_FLAG_BEGAN_CROSSING_ROAD | 191 |
| PED_FLAG_WARP_INTO_LEADERS_VEHICLE | 192 |
| PED_FLAG_DO_NOTHING_WHEN_ON_FOOT_BY_DEFAULT | 193 |
| PED_FLAG_USING_SCENARIO | 194 |
| PED_FLAG_VISIBLE_ON_SCREEN | 195 |
| PED_FLAG_DONT_COLLIDE_WITH_KINEMATIC | 196 |
| PED_FLAG_ACTIVATE_ON_SWITCH_FROM_LOW_PHYSICS_LOD | 197 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_ON_PED_COLLISION_WHEN_DEAD | 198 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_ON_VEHICLE_COLLISION_WHEN_DEAD | 199 |
| PED_FLAG_HAS_BEEN_IN_ARMED_COMBAT | 200 |
| PED_FLAG_USE_DIMINISHING_AMMO_RATE | 201 |
| PED_FLAG_AVOIDANCE_IGNORE_ALL | 202 |
| PED_FLAG_AVOIDANCE_IGNORED_BY_ALL | 203 |
| PED_FLAG_AVOIDANCE_IGNORE_GROUP1 | 204 |
| PED_FLAG_AVOIDANCE_MEMBER_OF_GROUP1 | 205 |
| PED_FLAG_FORCED_TO_USE_SPECIFIC_GROUP_SEAT_INDEX | 206 |
| PED_FLAG_LOW_PHYSICS_LOD_MAY_PLACE_ON_NAV_MESH | 207 |
| PED_FLAG_DISABLE_EXPLOSION_REACTIONS | 208 |
| PED_FLAG_DODGED_PLAYER | 209 |
| PED_FLAG_WAITING_FOR_PLAYER_CONTROL_INTERRUPT | 210 |
| PED_FLAG_FORCED_TO_STAY_IN_COVER | 211 |
| PED_FLAG_GENERATES_SOUND_EVENTS | 212 |
| PED_FLAG_LISTENS_TO_SOUND_EVENTS | 213 |
| PED_FLAG_ALLOW_TO_BE_TARGETED_IN_A_VEHICLE | 214 |
| PED_FLAG_WAIT_FOR_DIRECT_ENTRY_POINT_TO_BE_FREE_WHEN_EXITING | 215 |
| PED_FLAG_ONLY_REQUIRE_ONE_PRESS_TO_EXIT_VEHICLE | 216 |
| PED_FLAG_FORCE_EXIT_TO_SKY_DIVE | 217 |
| PED_FLAG_STEERS_AROUND_VEHICLES | 218 |
| PED_FLAG_ALLOW_PED_IN_VEHICLES_OVERRIDE_TASK_FLAGS | 219 |
| PED_FLAG_DONT_ENTER_LEADERS_VEHICLE | 220 |
| PED_FLAG_DISABLE_EXIT_TO_SKY_DIVE | 221 |
| PED_FLAG_SCRIPT_HAS_DISABLED_COLLISION | 222 |
| PED_FLAG_USE_AMBIENT_MODEL_SCALING | 223 |
| PED_FLAG_DONT_WATCH_FIRST_ON_NEXT_HURRY_AWAY | 224 |
| PED_FLAG_DISABLE_POTENTIAL_TO_BE_WALKED_INTO_RESPONSE | 225 |
| PED_FLAG_DISABLE_PED_AVOIDANCE | 226 |
| PED_FLAG_FORCE_RAGDOLL_UPON_DEATH | 227 |
| PED_FLAG_CAN_LOSE_PROPS_ON_DAMAGE | 228 |
| PED_FLAG_DISABLE_PANIC_IN_VEHICLE | 229 |
| PED_FLAG_ALLOWED_TO_DETACH_TRAILER | 230 |
| PED_FLAG_HAS_SHOT_BEEN_REACTED_TO_FROM_FRONT | 231 |
| PED_FLAG_HAS_SHOT_BEEN_REACTED_TO_FROM_BACK | 232 |
| PED_FLAG_HAS_SHOT_BEEN_REACTED_TO_FROM_LEFT | 233 |
| PED_FLAG_HAS_SHOT_BEEN_REACTED_TO_FROM_RIGHT | 234 |
| PED_FLAG_ALLOW_BLOCK_DEAD_PED_RAGDOLL_ACTIVATION | 235 |
| PED_FLAG_IS_HOLDING_PROP | 236 |
| PED_FLAG_BLOCKS_PATHING_WHEN_DEAD | 237 |
| PED_FLAG_FORCE_PLAY_NORMAL_SCENARIO_EXIT_ON_NEXT_SCRIPT_COMMAND | 238 |
| PED_FLAG_FORCE_PLAY_IMMEDIATE_SCENARIO_EXIT_ON_NEXT_SCRIPT_COMMAND | 239 |
| PED_FLAG_FORCE_SKIN_CHARACTER_CLOTH | 240 |
| PED_FLAG_LEAVE_ENGINE_ON_WHEN_EXITING_VEHICLES | 241 |
| PED_FLAG_PHONE_DISABLE_TEXTING_ANIMATIONS | 242 |
| PED_FLAG_PHONE_DISABLE_TALKING_ANIMATIONS | 243 |
| PED_FLAG_PHONE_DISABLE_CAMERA_ANIMATIONS | 244 |
| PED_FLAG_DISABLE_BLIND_FIRING_IN_SHOT_REACTIONS | 245 |
| PED_FLAG_ALLOW_NEARBY_COVER_USAGE | 246 |
| PED_FLAG_IN_STRAFE_TRANSITION | 247 |
| PED_FLAG_CAN_PLAY_IN_CAR_IDLES | 248 |
| PED_FLAG_CAN_ATTACK_NON_WANTED_PLAYER_AS_LAW | 249 |
| PED_FLAG_WILL_TAKE_DAMAGE_WHEN_VEHICLE_CRASHES | 250 |
| PED_FLAG_AI_CAN_DRIVE_PLAYER_AS_REAR_PASSENGER | 251 |
| PED_FLAG_PLAYER_CAN_JACK_FRIENDLY_PLAYERS | 252 |
| PED_FLAG_ON_STAIRS | 253 |
| PED_FLAG_SIMULATING_AIMING | 254 |
| PED_FLAG_AI_DRIVER_ALLOW_FRIENDLY_PASSENGER_SEAT_ENTRY | 255 |
| PED_FLAG_PARENT_CAR_IS_BEING_REMOVED | 256 |
| PED_FLAG_ALLOW_MISSION_PED_TO_USE_INJURED_MOVEMENT | 257 |
| PED_FLAG_CAN_LOSE_HELMET_ON_DAMAGE | 258 |
| PED_FLAG_NEVER_DO_SCENARIO_EXIT_PROBE_CHECKS | 259 |
| PED_FLAG_SUPPRESS_LOW_L_O_D_RAGDOLL_SWITCH_WHEN_CORPSE_SETTLES | 260 |
| PED_FLAG_PREVENT_USING_LOWER_PRIORITY_SEATS | 261 |
| PED_FLAG_JUST_LEFT_VEHICLE_NEEDS_RESET | 262 |
| PED_FLAG_TELEPORT_IF_CANT_REACH_PLAYER | 263 |
| PED_FLAG_PEDS_IN_VEHICLE_POSITION_NEEDS_RESET | 264 |
| PED_FLAG_PEDS_FULLY_IN_SEAT | 265 |
| PED_FLAG_ALLOW_PLAYER_LOCK_ON_IF_FRIENDLY | 266 |
| PED_FLAG_USE_CAMERA_HEADING_FOR_DESIRED_DIRECTION_LOCK_ON_TEST | 267 |
| PED_FLAG_TELEPORT_TO_LEADER_VEHICLE | 268 |
| PED_FLAG_AVOIDANCE_IGNORE_WEIRD_PED_BUFFER | 269 |
| PED_FLAG_ON_STAIR_SLOPE | 270 |
| PED_FLAG_HAS_PLAYED_N_M_GETUP | 271 |
| PED_FLAG_DONT_BLIP_COP | 272 |
| PED_FLAG_SPAWNED_AT_EXTENDED_RANGE_SCENARIO | 273 |
| PED_FLAG_WALK_ALONGSIDE_LEADER_WHEN_CLOSE | 274 |
| PED_FLAG_KILL_WHEN_TRAPPED | 275 |
| PED_FLAG_EDGE_DETECTED | 276 |
| PED_FLAG_ALWAYS_WAKE_UP_PHYSICS_OF_INTERSECTED_PEDS | 277 |
| PED_FLAG_EQUIPPED_AMBIENT_LOAD_OUT_WEAPON | 278 |
| PED_FLAG_AVOID_TEAR_GAS | 279 |
| PED_FLAG_STOPPED_SPEECH_UPON_FREEZING | 280 |
| PED_FLAG_DISABLE_GO_TO_WRITHE_WHEN_INJURED | 281 |
| PED_FLAG_ONLY_USE_FORCED_SEAT_WHEN_ENTERING_HELI_IN_GROUP | 282 |
| PED_FLAG_THROWN_FROM_VEHICLE_DUE_TO_EXHAUSTION | 283 |
| PED_FLAG_UPDATE_ENCLOSED_SEARCH_REGION | 284 |
| PED_FLAG_DISABLE_WEIRD_PED_EVENTS | 285 |
| PED_FLAG_SHOULD_CHARGE_NOW | 286 |
| PED_FLAG_RAGDOLLING_ON_BOAT | 287 |
| PED_FLAG_HAS_BRANDISHED_WEAPON | 288 |
| PED_FLAG_ALLOW_MINOR_REACTIONS_AS_MISSION_PED | 289 |
| PED_FLAG_BLOCK_DEAD_BODY_SHOCKING_EVENTS_WHEN_DEAD | 290 |
| PED_FLAG_PED_HAS_BEEN_SEEN | 291 |
| PED_FLAG_PED_IS_IN_REUSE_POOL | 292 |
| PED_FLAG_PED_WAS_REUSED | 293 |
| PED_FLAG_DISABLE_SHOCKING_EVENTS | 294 |
| PED_FLAG_MOVED_USING_LOW_LOD_PHYSICS_SINCE_LAST_ACTIVE | 295 |
| PED_FLAG_NEVER_REACT_TO_PED_ON_ROOF | 296 |
| PED_FLAG_FORCE_PLAY_FLEE_SCENARIO_EXIT_ON_NEXT_SCRIPT_COMMAND | 297 |
| PED_FLAG_JUST_BUMPED_INTO_VEHICLE | 298 |
| PED_FLAG_DISABLE_SHOCKING_DRIVING_ON_PAVEMENT_EVENTS | 299 |
| PED_FLAG_SHOULD_THROW_SMOKE_NOW | 300 |
| PED_FLAG_DISABLE_PED_CONSTRAINTS | 301 |
| PED_FLAG_FORCE_INITIAL_PEEK_IN_COVER | 302 |
| PED_FLAG_CREATED_BY_DISPATCH | 303 |
| PED_FLAG_POINT_GUN_LEFT_HAND_SUPPORTING | 304 |
| PED_FLAG_DISABLE_JUMPING_FROM_VEHICLES_AFTER_LEADER | 305 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FROM_PLAYER_PED_IMPACT | 306 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FROM_AI_RAGDOLL_IMPACT | 307 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FROM_PLAYER_RAGDOLL_IMPACT | 308 |
| PED_FLAG_DISABLE_QUADRUPED_SPRING | 309 |
| PED_FLAG_IS_IN_CLUSTER | 310 |
| PED_FLAG_SHOUT_TO_GROUP_ON_PLAYER_MELEE | 311 |
| PED_FLAG_IGNORED_BY_AUTO_OPEN_DOORS | 312 |
| PED_FLAG_PREFER_INJURED_GETUP | 313 |
| PED_FLAG_FORCE_IGNORE_MELEE_ACTIVE_COMBATANT | 314 |
| PED_FLAG_CHECK_LO_S_FOR_SOUND_EVENTS | 315 |
| PED_FLAG_JACKED_ABANDONED_CAR | 316 |
| PED_FLAG_CAN_SAY_FOLLOWED_BY_PLAYER_AUDIO | 317 |
| PED_FLAG_ACTIVATE_RAGDOLL_FROM_MINOR_PLAYER_CONTACT | 318 |
| PED_FLAG_HAS_PORTABLE_PICKUP_ATTACHED | 319 |
| PED_FLAG_FORCE_POSE_CHARACTER_CLOTH | 320 |
| PED_FLAG_HAS_CLOTH_COLLISION_BOUNDS | 321 |
| PED_FLAG_HAS_HIGH_HEELS | 322 |
| PED_FLAG_TREAT_AS_AMBIENT_PED_FOR_DRIVER_LOCK_ON | 323 |
| PED_FLAG_DONT_BEHAVE_LIKE_LAW | 324 |
| PED_FLAG_SPAWNED_AT_SCENARIO | 325 |
| PED_FLAG_DISABLE_POLICE_INVESTIGATING_BODY | 326 |
| PED_FLAG_DISABLE_WRITHE_SHOOT_FROM_GROUND | 327 |
| PED_FLAG_LOWER_PRIORITY_OF_WARP_SEATS | 328 |
| PED_FLAG_DISABLE_TALK_TO | 329 |
| PED_FLAG_DONT_BLIP | 330 |
| PED_FLAG_IS_SWITCHING_WEAPON | 331 |
| PED_FLAG_IGNORE_LEG_IK_RESTRICTIONS | 332 |
| PED_FLAG_SCRIPT_FORCE_NO_TIMESLICE_INTELLIGENCE_UPDATE | 333 |
| PED_FLAG_JACKED_OUT_OF_MY_VEHICLE | 334 |
| PED_FLAG_WENT_INTO_COMBAT_AFTER_BEING_JACKED | 335 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FOR_VEHICLE_GRAB | 336 |
| PED_FLAG_FORCE_PACKAGE_CHARACTER_CLOTH | 337 |
| PED_FLAG_DONT_REMOVE_WITH_VALID_ORDER | 338 |
| PED_FLAG_ALLOW_TASK_DO_NOTHING_TIMESLICING | 339 |
| PED_FLAG_FORCED_TO_STAY_IN_COVER_DUE_TO_PLAYER_SWITCH | 340 |
| PED_FLAG_FORCE_PRONE_CHARACTER_CLOTH | 341 |
| PED_FLAG_NOT_ALLOWED_TO_JACK_ANY_PLAYERS | 342 |
| PED_FLAG_IN_TO_STRAFE_TRANSITION | 343 |
| PED_FLAG_KILLED_BY_STANDARD_MELEE | 344 |
| PED_FLAG_ALWAYS_LEAVE_TRAIN_UPON_ARRIVAL | 345 |
| PED_FLAG_FORCE_PLAY_DIRECTED_NORMAL_SCENARIO_EXIT_ON_NEXT_SCRIPT_COMMAND | 346 |
| PED_FLAG_ONLY_WRITHE_FROM_WEAPON_DAMAGE | 347 |
| PED_FLAG_USE_SLO_MO_BLOOD_VFX | 348 |
| PED_FLAG_EQUIP_JETPACK | 349 |
| PED_FLAG_PREVENT_DRAGGED_OUT_OF_CAR_THREAT_RESPONSE | 350 |
| PED_FLAG_SCRIPT_HAS_COMPLETELY_DISABLED_COLLISION | 351 |
| PED_FLAG_NEVER_DO_SCENARIO_NAV_CHECKS | 352 |
| PED_FLAG_FORCE_SYNCHRONOUS_SCENARIO_EXIT_CHECKING | 353 |
| PED_FLAG_THROWING_GRENADE_WHILE_AIMING | 354 |
| PED_FLAG_HEADBOB_TO_RADIO_ENABLED | 355 |
| PED_FLAG_FORCE_DEEP_SURFACE_CHECK | 356 |
| PED_FLAG_DISABLE_DEEP_SURFACE_ANIMS | 357 |
| PED_FLAG_DONT_BLIP_NOT_SYNCED | 358 |
| PED_FLAG_IS_DUCKING_IN_VEHICLE | 359 |
| PED_FLAG_PREVENT_AUTO_SHUFFLE_TO_TURRET_SEAT | 360 |
| PED_FLAG_DISABLE_EVENT_INTERIOR_STATUS_CHECK | 361 |
| PED_FLAG_HAS_RESERVE_PARACHUTE | 362 |
| PED_FLAG_USE_RESERVE_PARACHUTE | 363 |
| PED_FLAG_TREAT_DISLIKE_AS_HATE_WHEN_IN_COMBAT | 364 |
| PED_FLAG_ONLY_UPDATE_TARGET_WANTED_IF_SEEN | 365 |
| PED_FLAG_ALLOW_AUTO_SHUFFLE_TO_DRIVERS_SEAT | 366 |
| PED_FLAG_DONT_ACTIVATE_RAGDOLL_FROM_SMOKE_GRENADE | 367 |
| PED_FLAG_LINK_M_B_R_TO_OWNER_ON_CHAIN | 368 |
| PED_FLAG_AMBIENT_FRIEND_BUMPED_BY_PLAYER | 369 |
| PED_FLAG_AMBIENT_FRIEND_BUMPED_BY_PLAYER_VEHICLE | 370 |
| PED_FLAG_IN_F_P_S_UNHOLSTER_TRANSITION | 371 |
| PED_FLAG_PREVENT_REACTING_TO_SILENCED_CLONE_BULLETS | 372 |
| PED_FLAG_DISABLE_INJURED_CRY_FOR_HELP_EVENTS | 373 |
| PED_FLAG_NEVER_LEAVE_TRAIN | 374 |
| PED_FLAG_DONT_DROP_JETPACK_ON_DEATH | 375 |
| PED_FLAG_USE_F_P_S_UNHOLSTER_TRANSITION_DURING_COMBAT_ROLL | 376 |
| PED_FLAG_EXITING_F_P_S_COMBAT_ROLL | 377 |
| PED_FLAG_SCRIPT_HAS_CONTROL_OF_PLAYER | 378 |
| PED_FLAG_PLAY_F_P_S_IDLE_FIDGETS_FOR_PROJECTILE | 379 |
| PED_FLAG_DISABLE_AUTO_EQUIP_HELMETS_IN_BIKES | 380 |
| PED_FLAG_DISABLE_AUTO_EQUIP_HELMETS_IN_AIRCRAFT | 381 |
| PED_FLAG_WAS_PLAYING_F_P_S_GETUP | 382 |
| PED_FLAG_WAS_PLAYING_F_P_S_MELEE_ACTION_RESULT | 383 |
| PED_FLAG_PREFER_NO_PRIORITY_REMOVAL | 384 |
| PED_FLAG_F_P_S_FIDGETS_ABORTED_ON_FIRE | 385 |
| PED_FLAG_FORCE_F_P_S_I_K_WITH_UPPER_BODY_ANIM | 386 |
| PED_FLAG_SWITCHING_CHARACTERS_IN_FIRST_PERSON | 387 |
| PED_FLAG_IS_CLIMBING_LADDER | 388 |
| PED_FLAG_HAS_BARE_FEET | 389 |
| PED_FLAG_UNUSED_2 | 390 |
| PED_FLAG_GO_ON_WITHOUT_VEHICLE_IF_IT_IS_UNABLE_TO_GET_BACK_TO_ROAD | 391 |
| PED_FLAG_BLOCK_DROPPING_HEALTH_SNACKS_ON_DEATH | 392 |
| PED_FLAG_RESET_LAST_VEHICLE_ON_VEHICLE_EXIT | 393 |
| PED_FLAG_FORCE_THREAT_RESPONSE_TO_NON_FRIEND_TO_FRIEND_MELEE_ACTIONS | 394 |
| PED_FLAG_DONT_RESPOND_TO_RANDOM_PEDS_DAMAGE | 395 |
| PED_FLAG_ALLOW_CONTINUOUS_THREAT_RESPONSE_WANTED_LEVEL_UPDATES | 396 |
| PED_FLAG_KEEP_TARGET_LOSS_RESPONSE_ON_CLEANUP | 397 |
| PED_FLAG_PLAYERS_DONT_DRAG_ME_OUT_OF_CAR | 398 |
| PED_FLAG_BROADCAST_REPONDED_TO_THREAT_WHEN_GOING_TO_POINT_SHOOTING | 399 |
| PED_FLAG_IGNORE_PED_TYPE_FOR_IS_FRIENDLY_WITH | 400 |
| PED_FLAG_TREAT_NON_FRIENDLY_AS_HATE_WHEN_IN_COMBAT | 401 |
| PED_FLAG_DONT_LEAVE_VEHICLE_IF_LEADER_NOT_IN_VEHICLE | 402 |
| PED_FLAG_CHANGE_FROM_PERMANENT_TO_AMBIENT_POP_TYPE_ON_MIGRATION | 403 |
| PED_FLAG_ALLOW_MELEE_REACTION_IF_MELEE_PROOF_IS_ON | 404 |
| PED_FLAG_USING_LOWRIDER_LEANS | 405 |
| PED_FLAG_USING_ALTERNATE_LOWRIDER_LEANS | 406 |
| PED_FLAG_USE_NORMAL_EXPLOSION_DAMAGE_WHEN_BLOWN_UP_IN_VEHICLE | 407 |
| PED_FLAG_DISABLE_HOMING_MISSILE_LOCK_FOR_VEHICLE_PED_INSIDE | 408 |
| PED_FLAG_DISABLE_TAKE_OFF_SCUBA_GEAR | 409 |
| PED_FLAG_IGNORE_MELEE_FIST_WEAPON_DAMAGE_MULT | 410 |
| PED_FLAG_LAW_PEDS_CAN_FLEE_FROM_NON_WANTED_PLAYER | 411 |
| PED_FLAG_FORCE_BLIP_SECURITY_PEDS_IF_PLAYER_IS_WANTED | 412 |
| PED_FLAG_IS_HOLSTERING_WEAPON | 413 |
| PED_FLAG_USE_GO_TO_POINT_FOR_SCENARIO_NAVIGATION | 414 |
| PED_FLAG_DONT_CLEAR_LOCAL_PASSENGERS_WANTED_LEVEL | 415 |
| PED_FLAG_BLOCK_AUTO_SWAP_ON_WEAPON_PICKUPS | 416 |
| PED_FLAG_THIS_PED_IS_A_TARGET_PRIORITY_FOR_AI | 417 |
| PED_FLAG_IS_SWITCHING_HELMET_VISOR | 418 |
| PED_FLAG_FORCE_HELMET_VISOR_SWITCH | 419 |
| PED_FLAG_IS_PERFORMING_VEHICLE_MELEE | 420 |
| PED_FLAG_USE_OVERRIDE_FOOTSTEP_PT_FX | 421 |
| PED_FLAG_DISABLE_VEHICLE_COMBAT | 422 |
| PED_FLAG_TREAT_AS_FRIENDLY_FOR_TARGETING_AND_DAMAGE | 423 |
| PED_FLAG_ALLOW_BIKE_ALTERNATE_ANIMATIONS | 424 |
| PED_FLAG_TREAT_AS_FRIENDLY_FOR_TARGETING_AND_DAMAGE_NON_SYNCED | 425 |
| PED_FLAG_USE_LOCKPICK_VEHICLE_ENTRY_ANIMATIONS | 426 |
| PED_FLAG_IGNORE_INTERIOR_CHECK_FOR_SPRINTING | 427 |
| PED_FLAG_SWAT_HELI_SPAWN_WITHIN_LAST_SPOTTED_LOCATION | 428 |
| PED_FLAG_DISABLE_START_ENGINE | 429 |
| PED_FLAG_IGNORE_BEING_ON_FIRE | 430 |
| PED_FLAG_DISABLE_TURRET_OR_REAR_SEAT_PREFERENCE | 431 |
| PED_FLAG_DISABLE_WANTED_HELICOPTER_SPAWNING | 432 |
| PED_FLAG_USE_TARGET_PERCEPTION_FOR_CREATING_AIMED_AT_EVENTS | 433 |
| PED_FLAG_DISABLE_HOMING_MISSILE_LOCKON | 434 |
| PED_FLAG_FORCE_IGNORE_MAX_MELEE_ACTIVE_SUPPORT_COMBATANTS | 435 |
| PED_FLAG_STAY_IN_DEFENSIVE_AREA_WHEN_IN_VEHICLE | 436 |
| PED_FLAG_DONT_SHOUT_TARGET_POSITION | 437 |
| PED_FLAG_DISABLE_HELMET_ARMOR | 438 |
| PED_FLAG_CREATED_BY_CONCEALED_PLAYER | 439 |
| PED_FLAG_PERMANENTLY_DISABLE_POTENTIAL_TO_BE_WALKED_INTO_RESPONSE | 440 |
| PED_FLAG_PREVENT_VEH_EXIT_DUE_TO_INVALID_WEAPON | 441 |
| PED_FLAG_IGNORE_NET_SESSION_FRIENDLY_FIRE_CHECK_FOR_ALLOW_DAMAGE | 442 |
| PED_FLAG_DONT_LEAVE_COMBAT_IF_TARGET_PLAYER_IS_ATTACKED_BY_POLICE | 443 |
| PED_FLAG_CHECK_LOCKED_BEFORE_WARP | 444 |
| PED_FLAG_DONT_SHUFFLE_IN_VEHICLE_TO_MAKE_ROOM | 445 |
| PED_FLAG_GIVE_WEAPON_ON_GETUP | 446 |
| PED_FLAG_DONT_HIT_VEHICLE_WITH_PROJECTILES | 447 |
| PED_FLAG_DISABLE_FORCED_ENTRY_FOR_OPEN_VEHICLES_FROM_TRY_LOCKED_DOOR | 448 |
| PED_FLAG_FIRES_DUMMY_ROCKETS | 449 |
| PED_FLAG_PED_IS_ARRESTING | 450 |
| PED_FLAG_IS_DECOY_PED | 451 |
| PED_FLAG_HAS_ESTABLISHED_DECOY | 452 |
| PED_FLAG_BLOCK_DISPATCHED_HELICOPTERS_FROM_LANDING | 453 |
| PED_FLAG_DONT_CRY_FOR_HELP_ON_STUN | 454 |
| PED_FLAG_HIT_BY_TRANQ_WEAPON | 455 |
| PED_FLAG_CAN_BE_INCAPACITATED | 456 |
| PED_FLAG_FORCED_AIM_FROM_ARREST | 457 |
| PED_FLAG_DONT_CHANGE_TARGET_FROM_MELEE | 458 |
| PED_FLAG_DISABLE_HEALTH_REGENERATION_WHEN_STUNNED | 459 |
| PED_FLAG_RAGDOLL_FLOATS_INDEFINITELY | 460 |
| PED_FLAG_BLOCK_ELECTRIC_WEAPON_DAMAGE | 461 |

## Config Flag Enum

```ts
export enum PedConfigFlag {
    CreatedByFactory = 0,
    CanBeShotInVehicle = 1,
    NoCriticalHits = 2,
    DrownsInWater = 3,
    DrownsInSinkingVehicle = 4,
    DiesInstantlyWhenSwimming = 5,
    HasBulletProofVest = 6,
    UpperBodyDamageAnimsOnly = 7,
    NeverFallOffSkis = 8,
    NeverEverTargetThisPed = 9,
    ThisPedIsATargetPriority = 10,
    TargettableWithNoLos = 11,
    DoesntListenToPlayerGroupCommands = 12,
    NeverLeavesGroup = 13,
    DoesntDropWeaponsWhenDead = 14,
    SetDelayedWeaponAsCurrent = 15,
    KeepTasksAfterCleanUp = 16,
    BlockNonTemporaryEvents = 17,
    HasAScriptBrain = 18,
    WaitingForScriptBrainToLoad = 19,
    AllowMedicsToReviveMe = 20,
    MoneyHasBeenGivenByScript = 21,
    NotAllowedToCrouch = 22,
    DeathPickupsPersist = 23,
    IgnoreSeenMelee = 24,
    ForceDieIfInjured = 25,
    DontDragMeOutCar = 26,
    StayInCarOnJack = 27,
    ForceDieInCar = 28,
    GetOutUndriveableVehicle = 29,
    WillRemainOnBoatAfterMissionEnds = 30,
    DontStoreAsPersistent = 31,
    WillFlyThroughWindscreen = 32,
    DieWhenRagdoll = 33,
    HasHelmet = 34,
    UseHelmet = 35,
    DontTakeOffHelmet = 36,
    HideInCutscene = 37,
    PedIsEnemyToPlayer = 38,
    DisableEvasiveDives = 39,
    PedGeneratesDeadBodyEvents = 40,
    DontAttackPlayerWithoutWantedLevel = 41,
    DontInfluenceWantedLevel = 42,
    DisablePlayerLockon = 43,
    DisableLockonToRandomPeds = 44,
    AllowLockonToFriendlyPlayers = 45,
    DisableHornAudioWhenDead  = 46,
    PedBeingDeleted = 47,
    BlockWeaponSwitching = 48,
    BlockGroupPedAimedAtResponse = 49,
    WillFollowLeaderAnyMeans = 50,
    BlippedByScript = 51,
    DrawRadarVisualField = 52,
    StopWeaponFiringOnImpact = 53,
    DissableAutoFallOffTests = 54,
    SteerAroundDeadBodies = 55,
    ConstrainToNavMesh = 56,
    SyncingAnimatedProps = 57,
    IsFiring = 58,
    WasFiring = 59,
    IsStanding = 60,
    WasStanding = 61,
    InVehicle = 62,
    OnMount = 63,
    AttachedToVehicle = 64,
    IsSwimming = 65,
    WasSwimming = 66,
    IsSkiing = 67,
    IsSitting = 68,
    KilledByStealth = 69,
    KilledByTakedown = 70,
    Knockedout = 71,
    ClearRadarBlipOnDeath = 72,
    JustGotOffTrain = 73,
    JustGotOnTrain = 74,
    UsingCoverPoint = 75,
    IsInTheAir = 76,
    KnockedUpIntoAir = 77,
    IsAimingGun = 78,
    HasJustLeftCar = 79,
    TargetWhenInjuredAllowed = 80,
    CurrLeftFootCollNM = 81,
    PrevLeftFootCollNM = 82,
    CurrRightFootCollNM = 83,
    PrevRightFootCollNM = 84,
    HasBeenBumpedInCar = 85,
    InWaterTaskQuitToClimbLadder = 86,
    NMTwoHandedWeaponBothHandsConstrained = 87,
    CreatedBloodPoolTimer = 88,
    DontActivateRagdollFromAnyPedImpact = 89,
    GroupPedFailedToEnterCover = 90,
    AlreadyChattedOnPhone = 91,
    AlreadyReactedToPedOnRoof = 92,
    ForcePedLoadCover = 93,
    BlockCoweringInCover = 94,
    BlockPeekingInCover = 95,
    JustLeftCarNotCheckedForDoors = 96,
    VaultFromCover = 97,
    AutoConversationLookAts = 98,
    UsingCrouchedPedCapsule = 99,
    HasDeadPedBeenReported = 100,
    ForcedAim = 101,
    SteersAroundPeds = 102,
    SteersAroundObjects = 103,
    OpenDoorArmIK = 104,
    ForceReload = 105,
    DontActivateRagdollFromVehicleImpact = 106,
    DontActivateRagdollFromBulletImpact = 107,
    DontActivateRagdollFromExplosions = 108,
    DontActivateRagdollFromFire = 109,
    DontActivateRagdollFromElectrocution = 110,
    IsBeingDraggedToSafety = 111,
    HasBeenDraggedToSafety = 112,
    KeepWeaponHolsteredUnlessFired = 113,
    ForceScriptControlledKnockout = 114,
    FallOutOfVehicleWhenKilled = 115,
    GetOutBurningVehicle = 116,
    BumpedByPlayer = 117,
    RunFromFiresAndExplosions = 118,
    TreatAsPlayerDuringTargeting = 119,
    IsHandCuffed = 120,
    IsAnkleCuffed = 121,
    DisableMelee = 122,
    DisableUnarmedDrivebys = 123,
    JustGetsPulledOutWhenElectrocuted = 124,
    UNUSED_1 = 125,
    WillNotHotwireLawEnforcementVehicle = 126,
    WillCommandeerRatherThanJack = 127,
    CanBeAgitated = 128,
    ForcePedToFaceLeftInCover = 129,
    ForcePedToFaceRightInCover = 130,
    BlockPedFromTurningInCover = 131,
    KeepRelationshipGroupAfterCleanUp = 132,
    ForcePedToBeDragged = 133,
    PreventPedFromReactingToBeingJacked = 134,
    IsScuba = 135,
    WillArrestRatherThanJack = 136,
    RemoveDeadExtraFarAway = 137,
    RidingTrain = 138,
    ArrestResult = 139,
    CanAttackFriendly = 140,
    WillJackAnyPlayer = 141,
    BumpedByPlayerVehicle = 142,
    DodgedPlayerVehicle = 143,
    WillJackWantedPlayersRatherThanStealCar = 144,
    NoCopWantedAggro = 145,
    DisableLadderClimbing = 146,
    StairsDetected = 147,
    SlopeDetected = 148,
    HelmetHasBeenShot = 149,
    CowerInsteadOfFlee = 150,
    CanActivateRagdollWhenVehicleUpsideDown = 151,
    AlwaysRespondToCriesForHelp = 152,
    DisableBloodPoolCreation = 153,
    ShouldFixIfNoCollision = 154,
    CanPerformArrest = 155,
    CanPerformUncuff = 156,
    CanBeArrested = 157,
    MoverConstrictedByOpposingCollisions = 158,
    PlayerPreferFrontSeatMP = 159,
    DontActivateRagdollFromImpactObject = 160,
    DontActivateRagdollFromMelee = 161,
    DontActivateRagdollFromWaterJet = 162,
    DontActivateRagdollFromDrowning = 163,
    DontActivateRagdollFromFalling = 164,
    DontActivateRagdollFromRubberBullet = 165,
    IsInjured = 166,
    DontEnterVehiclesInPlayersGroup = 167,
    SwimmingTasksRunning = 168,
    PreventAllMeleeTaunts = 169,
    ForceDirectEntry = 170,
    AlwaysSeeApproachingVehicles = 171,
    CanDiveAwayFromApproachingVehicles = 172,
    AllowPlayerToInterruptVehicleEntryExit = 173,
    OnlyAttackLawIfPlayerIsWanted = 174,
    PlayerInContactWithKinematicPed = 175,
    PlayerInContactWithSomethingOtherThanKinematicPed = 176,
    PedsJackingMeDontGetIn = 177,
    AdditionalRappellingPed = 178,
    PedIgnoresAnimInterruptEvents = 179,
    IsInCustody = 180,
    ForceStandardBumpReactionThresholds = 181,
    LawWillOnlyAttackIfPlayerIsWanted = 182,
    IsAgitated = 183,
    PreventAutoShuffleToDriversSeat = 184,
    UseKinematicModeWhenStationary = 185,
    EnableWeaponBlocking = 186,
    HasHurtStarted = 187,
    DisableHurt = 188,
    PlayerIsWeird = 189,
    PedHadPhoneConversation = 190,
    BeganCrossingRoad = 191,
    WarpIntoLeadersVehicle = 192,
    DoNothingWhenOnFootByDefault = 193,
    UsingScenario = 194,
    VisibleOnScreen = 195,
    DontCollideWithKinematic = 196,
    ActivateOnSwitchFromLowPhysicsLod = 197,
    DontActivateRagdollOnPedCollisionWhenDead = 198,
    DontActivateRagdollOnVehicleCollisionWhenDead = 199,
    HasBeenInArmedCombat = 200,
    UseDiminishingAmmoRate = 201,
    Avoidance_Ignore_All = 202,
    Avoidance_Ignored_by_All = 203,
    Avoidance_Ignore_Group1 = 204,
    Avoidance_Member_of_Group1 = 205,
    ForcedToUseSpecificGroupSeatIndex = 206,
    LowPhysicsLodMayPlaceOnNavMesh = 207,
    DisableExplosionReactions = 208,
    DodgedPlayer = 209,
    WaitingForPlayerControlInterrupt = 210,
    ForcedToStayInCover = 211,
    GeneratesSoundEvents = 212,
    ListensToSoundEvents = 213,
    AllowToBeTargetedInAVehicle = 214,
    WaitForDirectEntryPointToBeFreeWhenExiting = 215,
    OnlyRequireOnePressToExitVehicle = 216,
    ForceExitToSkyDive = 217,
    SteersAroundVehicles = 218,
    AllowPedInVehiclesOverrideTaskFlags = 219,
    DontEnterLeadersVehicle = 220,
    DisableExitToSkyDive = 221,
    ScriptHasDisabledCollision = 222,
    UseAmbientModelScaling = 223,
    DontWatchFirstOnNextHurryAway = 224,
    DisablePotentialToBeWalkedIntoResponse = 225,
    DisablePedAvoidance = 226,
    ForceRagdollUponDeath = 227,
    CanLosePropsOnDamage = 228,
    DisablePanicInVehicle = 229,
    AllowedToDetachTrailer = 230,
    HasShotBeenReactedToFromFront = 231,
    HasShotBeenReactedToFromBack = 232,
    HasShotBeenReactedToFromLeft = 233,
    HasShotBeenReactedToFromRight = 234,
    AllowBlockDeadPedRagdollActivation = 235,
    IsHoldingProp = 236,
    BlocksPathingWhenDead = 237,
    ForcePlayNormalScenarioExitOnNextScriptCommand = 238,
    ForcePlayImmediateScenarioExitOnNextScriptCommand = 239,
    ForceSkinCharacterCloth = 240,
    LeaveEngineOnWhenExitingVehicles = 241,
    PhoneDisableTextingAnimations = 242,
    PhoneDisableTalkingAnimations = 243,
    PhoneDisableCameraAnimations = 244,
    DisableBlindFiringInShotReactions = 245,
    AllowNearbyCoverUsage = 246,
    InStrafeTransition = 247,
    CanPlayInCarIdles = 248,
    CanAttackNonWantedPlayerAsLaw = 249,
    WillTakeDamageWhenVehicleCrashes = 250,
    AICanDrivePlayerAsRearPassenger = 251,
    PlayerCanJackFriendlyPlayers = 252,
    OnStairs = 253,
    SimulatingAiming = 254,
    AIDriverAllowFriendlyPassengerSeatEntry = 255,
    ParentCarIsBeingRemoved = 256,
    AllowMissionPedToUseInjuredMovement = 257,
    CanLoseHelmetOnDamage = 258,
    NeverDoScenarioExitProbeChecks = 259,
    SuppressLowLODRagdollSwitchWhenCorpseSettles = 260,
    PreventUsingLowerPrioritySeats = 261,
    JustLeftVehicleNeedsReset = 262,
    TeleportIfCantReachPlayer = 263,
    PedsInVehiclePositionNeedsReset = 264,
    PedsFullyInSeat = 265,
    AllowPlayerLockOnIfFriendly = 266,
    UseCameraHeadingForDesiredDirectionLockOnTest = 267,
    TeleportToLeaderVehicle = 268,
    Avoidance_Ignore_WeirdPedBuffer = 269,
    OnStairSlope = 270,
    HasPlayedNMGetup = 271,
    DontBlipCop = 272,
    SpawnedAtExtendedRangeScenario = 273,
    WalkAlongsideLeaderWhenClose = 274,
    KillWhenTrapped = 275,
    EdgeDetected = 276,
    AlwaysWakeUpPhysicsOfIntersectedPeds = 277,
    EquippedAmbientLoadOutWeapon = 278,
    AvoidTearGas = 279,
    StoppedSpeechUponFreezing = 280,
    DisableGoToWritheWhenInjured = 281,
    OnlyUseForcedSeatWhenEnteringHeliInGroup = 282,
    ThrownFromVehicleDueToExhaustion = 283,
    UpdateEnclosedSearchRegion = 284,
    DisableWeirdPedEvents = 285,
    ShouldChargeNow = 286,
    RagdollingOnBoat = 287,
    HasBrandishedWeapon = 288,
    AllowMinorReactionsAsMissionPed = 289,
    BlockDeadBodyShockingEventsWhenDead = 290,
    PedHasBeenSeen = 291,
    PedIsInReusePool = 292,
    PedWasReused = 293,
    DisableShockingEvents = 294,
    MovedUsingLowLodPhysicsSinceLastActive = 295,
    NeverReactToPedOnRoof = 296,
    ForcePlayFleeScenarioExitOnNextScriptCommand = 297,
    JustBumpedIntoVehicle = 298,
    DisableShockingDrivingOnPavementEvents = 299,
    ShouldThrowSmokeNow = 300,
    DisablePedConstraints = 301,
    ForceInitialPeekInCover = 302,
    CreatedByDispatch = 303,
    PointGunLeftHandSupporting = 304,
    DisableJumpingFromVehiclesAfterLeader = 305,
    DontActivateRagdollFromPlayerPedImpact = 306,
    DontActivateRagdollFromAiRagdollImpact = 307,
    DontActivateRagdollFromPlayerRagdollImpact = 308,
    DisableQuadrupedSpring = 309,
    IsInCluster = 310,
    ShoutToGroupOnPlayerMelee = 311,
    IgnoredByAutoOpenDoors = 312,
    PreferInjuredGetup = 313,
    ForceIgnoreMeleeActiveCombatant = 314,
    CheckLoSForSoundEvents = 315,
    JackedAbandonedCar = 316,
    CanSayFollowedByPlayerAudio = 317,
    ActivateRagdollFromMinorPlayerContact = 318,
    HasPortablePickupAttached = 319,
    ForcePoseCharacterCloth = 320,
    HasClothCollisionBounds = 321,
    HasHighHeels = 322,
    TreatAsAmbientPedForDriverLockOn = 323,
    DontBehaveLikeLaw = 324,
    SpawnedAtScenario = 325,
    DisablePoliceInvestigatingBody = 326,
    DisableWritheShootFromGround = 327,
    LowerPriorityOfWarpSeats = 328,
    DisableTalkTo = 329,
    DontBlip = 330,
    IsSwitchingWeapon = 331,
    IgnoreLegIkRestrictions = 332,
    ScriptForceNoTimesliceIntelligenceUpdate = 333,
    JackedOutOfMyVehicle = 334,
    WentIntoCombatAfterBeingJacked = 335,
    DontActivateRagdollForVehicleGrab = 336,
    ForcePackageCharacterCloth = 337,
    DontRemoveWithValidOrder = 338,
    AllowTaskDoNothingTimeslicing = 339,
    ForcedToStayInCoverDueToPlayerSwitch = 340,
    ForceProneCharacterCloth = 341,
    NotAllowedToJackAnyPlayers = 342,
    InToStrafeTransition = 343,
    KilledByStandardMelee = 344,
    AlwaysLeaveTrainUponArrival = 345,
    ForcePlayDirectedNormalScenarioExitOnNextScriptCommand = 346,
    OnlyWritheFromWeaponDamage = 347,
    UseSloMoBloodVfx = 348,
    EquipJetpack = 349,
    PreventDraggedOutOfCarThreatResponse = 350,
    ScriptHasCompletelyDisabledCollision = 351,
    NeverDoScenarioNavChecks = 352,
    ForceSynchronousScenarioExitChecking = 353,
    ThrowingGrenadeWhileAiming = 354,
    HeadbobToRadioEnabled = 355,
    ForceDeepSurfaceCheck = 356,
    DisableDeepSurfaceAnims = 357,
    DontBlipNotSynced = 358,
    IsDuckingInVehicle = 359,
    PreventAutoShuffleToTurretSeat = 360,
    DisableEventInteriorStatusCheck = 361,
    HasReserveParachute = 362,
    UseReserveParachute = 363,
    TreatDislikeAsHateWhenInCombat = 364,
    OnlyUpdateTargetWantedIfSeen = 365,
    AllowAutoShuffleToDriversSeat = 366,
    DontActivateRagdollFromSmokeGrenade = 367,
    LinkMBRToOwnerOnChain = 368,
    AmbientFriendBumpedByPlayer = 369,
    AmbientFriendBumpedByPlayerVehicle = 370,
    InFPSUnholsterTransition = 371,
    PreventReactingToSilencedCloneBullets = 372,
    DisableInjuredCryForHelpEvents = 373,
    NeverLeaveTrain = 374,
    DontDropJetpackOnDeath = 375,
    UseFPSUnholsterTransitionDuringCombatRoll = 376,
    ExitingFPSCombatRoll = 377,
    ScriptHasControlOfPlayer = 378,
    PlayFPSIdleFidgetsForProjectile = 379,
    DisableAutoEquipHelmetsInBikes = 380,
    DisableAutoEquipHelmetsInAircraft = 381,
    WasPlayingFPSGetup = 382,
    WasPlayingFPSMeleeActionResult = 383,
    PreferNoPriorityRemoval = 384,
    FPSFidgetsAbortedOnFire = 385,
    ForceFPSIKWithUpperBodyAnim = 386,
    SwitchingCharactersInFirstPerson = 387,
    IsClimbingLadder = 388,
    HasBareFeet = 389,
    UNUSED_2 = 390,
    GoOnWithoutVehicleIfItIsUnableToGetBackToRoad = 391,
    BlockDroppingHealthSnacksOnDeath = 392,
    ResetLastVehicleOnVehicleExit = 393,
    ForceThreatResponseToNonFriendToFriendMeleeActions = 394,
    DontRespondToRandomPedsDamage = 395,
    AllowContinuousThreatResponseWantedLevelUpdates = 396,
    KeepTargetLossResponseOnCleanup = 397,
    PlayersDontDragMeOutOfCar = 398,
    BroadcastRepondedToThreatWhenGoingToPointShooting = 399,
    IgnorePedTypeForIsFriendlyWith = 400,
    TreatNonFriendlyAsHateWhenInCombat = 401,
    DontLeaveVehicleIfLeaderNotInVehicle = 402,
    ChangeFromPermanentToAmbientPopTypeOnMigration = 403,
    AllowMeleeReactionIfMeleeProofIsOn = 404,
    UsingLowriderLeans = 405,
    UsingAlternateLowriderLeans = 406,
    UseNormalExplosionDamageWhenBlownUpInVehicle = 407,
    DisableHomingMissileLockForVehiclePedInside = 408,
    DisableTakeOffScubaGear = 409,
    IgnoreMeleeFistWeaponDamageMult = 410,
    LawPedsCanFleeFromNonWantedPlayer = 411,
    ForceBlipSecurityPedsIfPlayerIsWanted = 412,
    IsHolsteringWeapon = 413,
    UseGoToPointForScenarioNavigation = 414,
    DontClearLocalPassengersWantedLevel = 415,
    BlockAutoSwapOnWeaponPickups = 416,
    ThisPedIsATargetPriorityForAI = 417,
    IsSwitchingHelmetVisor = 418,
    ForceHelmetVisorSwitch = 419,
    IsPerformingVehicleMelee = 420,
    UseOverrideFootstepPtFx = 421,
    DisableVehicleCombat = 422,
    TreatAsFriendlyForTargetingAndDamage = 423,
    AllowBikeAlternateAnimations = 424,
    TreatAsFriendlyForTargetingAndDamageNonSynced = 425,
    UseLockpickVehicleEntryAnimations = 426,
    IgnoreInteriorCheckForSprinting = 427,
    SwatHeliSpawnWithinLastSpottedLocation = 428,
    DisableStartEngine = 429,
    IgnoreBeingOnFire = 430,
    DisableTurretOrRearSeatPreference = 431,
    DisableWantedHelicopterSpawning = 432,
    UseTargetPerceptionForCreatingAimedAtEvents = 433,
    DisableHomingMissileLockon = 434,
    ForceIgnoreMaxMeleeActiveSupportCombatants = 435,
    StayInDefensiveAreaWhenInVehicle = 436,
    DontShoutTargetPosition = 437,
    DisableHelmetArmor = 438,
    CreatedByConcealedPlayer = 439,
    PermanentlyDisablePotentialToBeWalkedIntoResponse = 440,
    PreventVehExitDueToInvalidWeapon = 441,
    IgnoreNetSessionFriendlyFireCheckForAllowDamage = 442,
    DontLeaveCombatIfTargetPlayerIsAttackedByPolice = 443,
    CheckLockedBeforeWarp = 444,
    DontShuffleInVehicleToMakeRoom = 445,
    GiveWeaponOnGetup = 446,
    DontHitVehicleWithProjectiles = 447,
    DisableForcedEntryForOpenVehiclesFromTryLockedDoor = 448,
    FiresDummyRockets = 449,
    PedIsArresting = 450,
    IsDecoyPed = 451,
    HasEstablishedDecoy = 452,
    BlockDispatchedHelicoptersFromLanding = 453,
    DontCryForHelpOnStun = 454,
    HitByTranqWeapon = 455,
    CanBeIncapacitated = 456,
    ForcedAimFromArrest = 457,
    DontChangeTargetFromMelee = 458,
    DisableHealthRegenerationWhenStunned = 459,
    RagdollFloatsIndefinitely = 460,
    BlockElectricWeaponDamage = 461
}
```
