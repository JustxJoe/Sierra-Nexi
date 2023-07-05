{
  "name": "Sierra",
  "settings": {
    "physics": {
      "gravity": [
        0,
        0,
        0
      ]
    },
    "render": {
      "fog_end": 1000,
      "fog_start": 700,
      "global_ambient": [
        0.6901960784313725,
        0.5450980392156862,
        0.7725490196078432
      ],
      "fog_color": [
        1,
        0.7372549019607844,
        0.47058823529411764
      ],
      "fog": "exp",
      "fog_density": 0.0001,
      "gamma_correction": 1,
      "tonemapping": 1,
      "exposure": 6,
      "skybox": 29307645,
      "skyboxIntensity": 6,
      "skyboxMip": 0,
      "lightmapSizeMultiplier": 16,
      "lightmapMaxResolution": 2048,
      "lightmapMode": 1
    }
  },
  "entities": {
    "6d984d2f-ab17-42b9-b521-7b1bfb7da4ca": {
      "name": "MapHolder",
      "parent": null,
      "resource_id": "6d984d2f-ab17-42b9-b521-7b1bfb7da4ca",
      "tags": [],
      "enabled": true,
      "components": {},
      "scale": [
        1,
        1,
        1
      ],
      "position": [
        0,
        0,
        0
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "children": [
        "1caaa160-0c94-472a-af19-bec519cc066b",
        "a84eb64b-ae5c-49f9-bb7c-a0746aae0286",
        "aa5d5ef8-2e97-4bcf-b6bb-077387e001cc",
        "530085dd-2cd2-44fa-9671-aaf03c491407",
        "24f386f4-26c1-4f50-8f1e-ad85d1a9dad3"
      ]
    },
    "1caaa160-0c94-472a-af19-bec519cc066b": {
      "position": [
        2,
        5.875436104271247,
        -2
      ],
      "scale": [
        1,
        1,
        1
      ],
      "name": "Light",
      "parent": "6d984d2f-ab17-42b9-b521-7b1bfb7da4ca",
      "resource_id": "1caaa160-0c94-472a-af19-bec519cc066b",
      "components": {
        "light": {
          "vsmBlurSize": 11,
          "normalOffsetBias": 0.05,
          "color": [
            0,
            0,
            0
          ],
          "outerConeAngle": 45,
          "castShadows": false,
          "intensity": 0,
          "bakeDir": true,
          "cookieAngle": 0,
          "cookieChannel": "rgb",
          "innerConeAngle": 40,
          "bake": false,
          "falloffMode": 0,
          "layers": [
            0,
            1000
          ],
          "cookieIntensity": 1,
          "vsmBias": 0.01,
          "vsmBlurMode": 1,
          "type": "directional",
          "cookieFalloff": true,
          "isStatic": false,
          "shadowUpdateMode": 1,
          "cookieScale": [
            1,
            1
          ],
          "affectLightmapped": false,
          "shadowBias": 0.2,
          "affectDynamic": true,
          "cookieAsset": null,
          "cookieOffset": [
            0,
            0
          ],
          "shadowResolution": 1024,
          "enabled": true,
          "range": 8,
          "shadowDistance": 200,
          "shadowType": 0
        }
      },
      "rotation": [
        -12.265983727178648,
        -25.330336720048,
        79.02529949719371
      ],
      "tags": [],
      "enabled": true,
      "children": []
    },
    "a84eb64b-ae5c-49f9-bb7c-a0746aae0286": {
      "name": "Map",
      "tags": [],
      "enabled": true,
      "resource_id": "a84eb64b-ae5c-49f9-bb7c-a0746aae0286",
      "parent": "6d984d2f-ab17-42b9-b521-7b1bfb7da4ca",
      "children": [
        "8d183a2b-89ba-4e0a-a7b6-5e115538223d",
        "183e2094-9acc-464e-adc0-06dc18fdbecc",
        "6741e083-782f-4c48-bcd9-ee7dea0f6f98",
        "9fe946be-a40e-4ea9-8527-c7b127b0bad8",
        "1e2e98a5-a985-43ec-a41a-1140de21e2f3",
        "a36ea639-f681-4c2f-9424-20f09e841194",
        "914189ba-f675-4bd2-a36a-c33de6cf47ee",
        "317a1d13-b11c-4f26-bede-e4324b7cf98a",
        "ed8f5360-faac-4431-975e-ba733fc8b3ff",
        "19fcf8e4-3829-4cb8-a69e-145cc0a9eaad",
        "07cf7750-86ee-4886-a513-6f064142f725",
        "7ebea48a-0275-4c9d-8807-98d8728ee864",
        "054d2c30-4353-4818-b99d-27546705b527"
      ],
      "position": [
        0,
        0,
        0
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "sound": {
          "enabled": true,
          "volume": 1,
          "pitch": 1,
          "positional": false,
          "refDistance": 1,
          "maxDistance": 10000,
          "rollOffFactor": 1,
          "distanceModel": "linear",
          "slots": {
            "1": {
              "name": "Ambient",
              "loop": true,
              "autoPlay": true,
              "overlap": false,
              "asset": 30975135,
              "startTime": 0,
              "duration": null,
              "volume": 0.85,
              "pitch": 1
            }
          }
        },
        "script": {
          "enabled": true,
          "order": [
            "ccd"
          ],
          "scripts": {
            "ccd": {
              "enabled": true,
              "attributes": {
                "motionThreshold": 1,
                "sweptSphereRadius": 0.2,
                "entities": [
                  "8d183a2b-89ba-4e0a-a7b6-5e115538223d",
                  "183e2094-9acc-464e-adc0-06dc18fdbecc",
                  "6741e083-782f-4c48-bcd9-ee7dea0f6f98",
                  "9fe946be-a40e-4ea9-8527-c7b127b0bad8",
                  "1e2e98a5-a985-43ec-a41a-1140de21e2f3",
                  "a36ea639-f681-4c2f-9424-20f09e841194"
                ]
              }
            }
          }
        }
      }
    },
    "8d183a2b-89ba-4e0a-a7b6-5e115538223d": {
      "position": [
        -9.418604835304055,
        0,
        2.731489419937134
      ],
      "scale": [
        238.1878801376834,
        0.4763757602753668,
        238.1878801376834
      ],
      "name": "Ground",
      "parent": "a84eb64b-ae5c-49f9-bb7c-a0746aae0286",
      "resource_id": "8d183a2b-89ba-4e0a-a7b6-5e115538223d",
      "components": {
        "model": {
          "layers": [
            0
          ],
          "isStatic": false,
          "castShadows": true,
          "castShadowsLightmap": false,
          "lightmapped": false,
          "materialAsset": 29542057,
          "receiveShadows": true,
          "enabled": true,
          "castShadowsLightMap": false,
          "asset": null,
          "type": "plane",
          "lightmapSizeMultiplier": 1,
          "batchGroupId": null
        },
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            120,
            0.01,
            120
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        },
        "script": {
          "enabled": true,
          "order": [
            "terrain"
          ],
          "scripts": {
            "terrain": {
              "enabled": true,
              "attributes": {
                "map": 30866540,
                "red": 30867252,
                "green": 30479676,
                "blue": 30867280,
                "redScale": [
                  60,
                  60
                ],
                "greenScale": [
                  60,
                  60
                ],
                "blueScale": [
                  35,
                  35
                ]
              }
            }
          }
        }
      },
      "rotation": [
        0,
        0,
        0
      ],
      "tags": [
        "Dirt"
      ],
      "enabled": true,
      "children": []
    },
    "5ad9b9f5-012c-446b-854b-e8171369c794": {
      "position": [
        -0.9662908511205579,
        2.548170424919154,
        12.768607284116841
      ],
      "scale": [
        20,
        1,
        20
      ],
      "name": "Ground",
      "parent": "ed8f5360-faac-4431-975e-ba733fc8b3ff",
      "resource_id": "5ad9b9f5-012c-446b-854b-e8171369c794",
      "components": {
        "model": {
          "layers": [
            0
          ],
          "isStatic": false,
          "castShadows": true,
          "castShadowsLightmap": false,
          "lightmapped": false,
          "materialAsset": 29542740,
          "receiveShadows": true,
          "enabled": true,
          "castShadowsLightMap": false,
          "asset": null,
          "type": "plane",
          "lightmapSizeMultiplier": 1,
          "batchGroupId": null
        },
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            10,
            0.01,
            10
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      },
      "rotation": [
        -90.00000113393138,
        -74.99999870487031,
        90.00000032354309
      ],
      "tags": [
        "Dirt"
      ],
      "enabled": true,
      "children": []
    },
    "914189ba-f675-4bd2-a36a-c33de6cf47ee": {
      "name": "Props",
      "tags": [],
      "enabled": true,
      "resource_id": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "parent": "a84eb64b-ae5c-49f9-bb7c-a0746aae0286",
      "children": [
        "4f8c80d2-a056-45da-abd0-79e6956db51d",
        "dce53cac-ecdc-4958-879e-432161d074cc",
        "1f74d11d-9bc1-43f1-9a8f-0334dbd45572",
        "d1011fa8-b4e4-4675-98f1-63884dd849a6",
        "d0676ba9-d9a8-41db-8a8c-cc87676ffdc9",
        "4aa495c4-0f75-4dc9-be2d-db79e57efb4a",
        "015a56f0-dba3-47ab-b334-59157214a713",
        "c3b137eb-4dbb-49ca-a0da-9df7ace9c551",
        "2a679e3a-32a9-4909-8d30-f1e3175dcf7e",
        "e682fb41-9409-4d68-80d3-2fce988b2359",
        "79da678c-3b16-4d35-9fb5-197d547e28ec",
        "00a693c6-fd64-4c02-bacb-7e39cf0a8d87",
        "97a12bdb-25f5-4834-b54c-497c8233bcb9",
        "006db230-ba94-4eb6-a29c-18bbebe6821a",
        "925664ff-a0fb-4c1a-b01b-4eb0035ff34e",
        "cd3185f4-cb57-4e68-888e-4022265bb263",
        "0b96baa0-5e59-4701-be11-a2d11d40e839",
        "2736f6ad-4f0a-400a-b302-ee8db853cf7e",
        "7cabc6b6-c813-4535-a2df-d1c5c084245a",
        "d42d7fec-5c48-4eac-bc65-1cbd39018dc8",
        "1515f39a-ad0b-4c86-8e35-373cebd7b10c",
        "08f67bd7-d800-4474-825e-65d372f79382",
        "41402653-f08d-45d6-8ac6-7884eb3a8a0c",
        "32381034-5b60-4e6a-a321-186500eb80cb",
        "2355f32d-0f96-4057-a24c-8081bacb437d",
        "46be8fca-ee06-4ae8-9ff8-30fd8e2e8c0d",
        "e161e018-b756-4a9a-8c8b-be5840e8d32b",
        "dc7d92df-4590-4a1c-9c54-4297db17ce24",
        "9a720aa6-52fe-4727-b03b-c039112afac6",
        "26ff3a19-04bd-4c65-ab31-7845008a7d88",
        "b4787ecd-cf6c-40d3-a60a-bfab4ecdd43a",
        "4bffc924-e9e0-4fed-a2d0-da90e74c8266",
        "28c27597-010d-403b-a465-1e39939a9faa",
        "7ffc593d-2601-40f7-914e-4eba66594ccc",
        "6571cf1e-0f64-4499-ae47-e84b9a48fd0b",
        "b8486825-7c9b-4941-a84a-f01cacb6158c",
        "3dcaff7c-7eac-4230-94cf-01604d895924",
        "179934aa-a9b0-4a59-82ff-5a95dd7b949a",
        "fc74e726-1791-4c70-8a35-b525e347f416",
        "3b522033-f114-4e10-8dec-d0a0e6904b3e",
        "98761754-edbb-4945-b71b-0332cc61b5b0",
        "df328856-ab85-446c-883c-aa867fa3ed9a",
        "ee30513d-2f16-4884-b02e-709c124b5b5b",
        "1d19ecb0-7353-4ce1-9a7c-77b4d4ccda25",
        "9f252ab7-173b-4152-b3a9-957cf7bf9eeb",
        "eff14bfa-96f5-4206-8ab2-fdb4ac796b6c",
        "fd87fc48-1404-4ca3-b463-f37114c3957c",
        "5f0ae9f4-0fb4-4282-9430-efca4b7c2122",
        "d6c684a1-ab56-46f1-841a-ae139e5ab8c8",
        "3f449c69-6fa7-40bd-ac85-e5e0455255ce",
        "bf988d9a-e37e-494e-9b64-43549d326319",
        "a54ab68b-baa0-4131-a4b6-2d7e44a0a3ec",
        "e8fb97a5-a778-49ff-b7e6-435b386a0763",
        "82d0e653-18da-4155-a1a9-7e1e3833768e",
        "55b57729-acfa-4e78-bd5b-ed4dc7033bde",
        "08fe5ace-019a-434d-86f6-6a47b31129f8",
        "180784ca-5ace-4e6d-879d-ba4ef9f1adb3",
        "178e75da-5e22-4320-b46c-0385ae30bcd2",
        "25fbd918-6a1a-4a05-9188-0ca0f2de3867",
        "6b75599a-ff8c-4001-9031-b57dd06fd1f6",
        "8cd0a054-dbdf-46d2-8fa8-96cab7f8e260",
        "213735c7-f714-4464-960b-c1faa1cde037",
        "a71ce0ab-f22f-4f75-8692-547d4f72527f",
        "c0924f99-993b-4bbb-bf8a-a61575410ad0",
        "e85d2a34-f589-4c48-8e45-2aafdfd988e4",
        "ba866499-c617-4665-bbbf-d442a8ce8609",
        "eda0223f-601e-4fdc-a944-37943bb2ac7f",
        "ebd1da03-0d1d-4d0d-bd59-9890a95e12c5",
        "906d4a5b-61d6-44ac-99e3-37e95caaa401",
        "e16eb3cd-0ab4-4d6a-8c01-1107e97192e0",
        "1af0f234-ea46-4865-ae94-05e041e8c114",
        "5ba3ac28-84d2-46f2-88f9-ca93ca192215",
        "a7a69edc-7c03-4f1d-8152-97702cdebb25",
        "6bc339cd-81a0-4470-939c-9a17c1250510",
        "f9f748ae-bad1-40fb-83eb-885c2b5e422c",
        "01abeffc-f2f3-4447-b48c-e9d58c318350",
        "945965f7-d1f7-43b9-b272-897112b6d19f",
        "cb671089-5c1c-4779-9408-796f9f3d74c8",
        "eda21872-0772-4912-a5a6-179dfd401780",
        "0277d182-89fa-460f-ba0a-24a021fdfec1",
        "06d9302d-2543-49ad-b524-173b3bd48276",
        "4ec03234-2d9f-49e6-abce-283a788de6d8",
        "8d3d7758-7b4d-44a3-a3a9-2ef627b90d2a",
        "edaa0f11-05a6-4354-8126-13f28df87e06",
        "bd24997b-b523-47fe-a5da-dcb9eb966780",
        "c51ffae1-b2bf-4906-866b-dae71b66d235",
        "0ef95f94-9b54-4686-82dd-62f5e3db9120",
        "c9f42087-a05e-408f-9527-502332f93260",
        "aa369f96-fdbc-4b2b-b8e5-515045ee4463",
        "b630031c-f13d-47b7-800c-81b4ad143df3",
        "5e77c6a2-a083-4d76-b81a-a92a9ad69ab5",
        "d229d8a2-f4d7-44dd-8c91-173531c4e88c",
        "98bf129c-6000-4e97-98ac-e3dd0ccd8aaa",
        "fd15a466-5ba8-4587-b000-2150c2bd2316",
        "3a1f54ea-f296-4341-9d0c-6cf9cf60cb3c",
        "f49febf7-79e8-4818-bfec-3ac3077dc1ee",
        "9d70669a-9faf-45c9-a579-151c5aa31bee",
        "6b0efa7b-3901-434f-b805-2b286381df9a",
        "0cca8fae-71d6-4fa0-a180-5e97c10d905f",
        "c5b1b8eb-9a41-47c5-aeda-9d62a7b996a8",
        "a88481a9-cd7e-481a-b270-ea665125f8f8",
        "e3dc16ac-1132-4c10-94ab-9dc1a0e5db70",
        "268f55b0-5cb9-49b9-9156-f0c2ecf682c6",
        "77d45c39-061c-4739-832d-a5a5e6818d76",
        "f87f0b32-c57a-4be7-925c-708d013b9fe6",
        "355f02b8-9584-4203-90bd-32e8f4c5bba3",
        "193956ac-0995-4e88-9680-77839ef61bcd",
        "5aee3488-71d5-4a35-867d-159e42819723",
        "acbfe81f-b51f-4aca-bcf5-030e25a1bdb6",
        "60a32e32-5d88-4453-8e66-b085912c47cb",
        "418f146b-5ee7-4077-8a4e-86011b1ead40",
        "0cb35937-b91b-4d24-b55c-8a4ee74fc2bd",
        "468a48f8-9ce1-4813-b919-b2b7bddae9cc",
        "3a195ed7-71c7-4b20-9d86-9c83c010b7ca",
        "5248ae10-aad9-488e-ae97-58e33ad161ad",
        "37640945-7ca5-4bec-8650-cf6dad28115a",
        "a255bdfe-ae6b-4dcc-8b6d-83cebc59217e",
        "34bc34f4-408f-41b9-aebd-863cbfb8fad1",
        "72dff8af-1a51-47fc-a3a4-30db7b6ab852",
        "8acaa78b-8273-4a0e-96aa-d9a417ae8ef0",
        "87b7237b-f4ad-4f52-9b3f-550cd085f7a5",
        "3971dcee-5d63-45d9-b143-47c85dc03982",
        "f9573a00-b768-4783-8c5a-833467192ff9",
        "ccdc80d1-748c-4f12-8507-fb76f7021ed9",
        "99a70f70-71c2-499b-9a7e-b6b0c7ed89e5",
        "b67dcb91-1d14-4325-a5d7-6f6db8ebd878",
        "6ee45802-111a-451c-9477-edd9d6ba88e0",
        "71530786-3b15-430e-9be0-144a52150634",
        "66c7a5c0-86d9-46e7-aa59-1c08c436cf27",
        "06e8aa66-5b83-4a92-bcce-54e7ab97f020",
        "78587634-4606-4b8c-870d-e8b4ac92fdc5",
        "d1abd9ac-ade3-428e-be53-2ed121f0761d",
        "4b9fead8-9e5e-4de8-b3e9-2d9a3b2eb771",
        "e0e86911-ad60-4bd2-9431-bcef58544dc4",
        "4885fd6b-f097-4d96-9cf4-d8efbb0b8c64",
        "bceb3fd9-e5f3-4534-9b9b-51cc81248eb9",
        "550d8cd7-5271-4e26-94e4-67527d9f4bbf",
        "ff9d2d1e-8c90-4bb9-a71e-61fa8ca0654a",
        "6bd26262-8743-44ea-97a8-e9985bc24a85",
        "7f280e84-1638-40a8-a807-34659d269c5e",
        "2829f820-8dd7-4ce5-a3ae-666af2bf1a55",
        "e26f434e-2ac0-4709-b2f6-707d28dade71",
        "f9131c11-3f56-4753-b1e4-159fbc9a0e36",
        "33c42951-aa4f-49d9-a983-2e8615163b4e",
        "885da80f-d239-4ab4-a2b0-ddd32bf6dfe1",
        "9c31ad4d-4b3d-42b0-a36f-257909b6d219",
        "43053649-9dc5-4ac1-b1b3-963f25e98b6f",
        "ae7c9690-2477-4ea0-afb6-01d450336848",
        "9b30987b-838a-43a3-bcda-8b87d89a7a5a",
        "0c07fc58-981b-4b2a-a908-24bd7a59bf86",
        "1023878b-4785-4f0b-ad56-a1b18fa65802",
        "59b72a6a-e34e-4e97-aef1-e860940a8a95",
        "a7082d8b-7dd8-410b-b396-3a02f5ef22d4",
        "fab77d8c-eb44-4e6b-97df-0c017fde6303",
        "4fe10cac-0b7e-4daa-b4f3-04604c6c478e",
        "bdbad0d1-f6ac-41c5-9359-c8bc6a76a04b",
        "5c25c133-3873-4169-8a4c-0dfab4266032",
        "b1fbbb03-0c1c-480d-a1d5-6d83fdcdfaef",
        "66f855c0-d587-48a9-81fe-0a3667306163",
        "62f94e3a-af47-43e1-bf07-200f195103ff",
        "bcf7a70a-66a3-43c7-9dde-e7d0075ddb35",
        "c6654fc0-e9ff-43de-b435-d107d8261aec",
        "8ac42b05-f78d-4167-b238-eb94da259623",
        "e0f2307d-d40a-413e-9062-b7b4c838a823",
        "75032b07-d344-42c0-9269-b65adfe21203",
        "af8d6d2c-9d79-492b-816f-e70e0e7ba470",
        "fcdbe068-1d30-4016-9b94-9374ad1e37c6",
        "5530f4ef-e787-4f32-81dd-814890c9647c",
        "6ac1028e-b662-488d-8e3a-001928d1c003",
        "bb062bc1-d668-40e2-97b9-3d94cb2d1d59",
        "64d98245-86e7-4106-9449-0b185b690a1e",
        "3ee4213c-3f8e-4e5e-938c-da505e4c8afc",
        "e5feda81-af00-467c-8901-517d1cf6017f",
        "fc55f80c-57f6-4ff8-a8d7-751c082ea925",
        "0ecbd550-7969-4ab7-a5e6-264f8490bd5d",
        "91752b3a-bef1-4d41-ae86-c385046c07df",
        "b518b1fa-6474-4008-84f9-2aeaaddd7180",
        "31296035-4097-4f2b-afaa-1c63cf6fb77c",
        "7b0f4bec-14d6-4fd5-a731-006305938406",
        "5a1e75cd-4b0a-4230-a729-b2064a4c8dca",
        "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
        "930cbf46-cd9f-4289-9f1e-6c498ee13094",
        "8b7751c4-49d6-492e-ae40-30ca6f5c8524",
        "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
        "012b26c2-273b-4cfc-833d-e3eb2977e985",
        "2250204c-8b4a-49ad-94cc-d12f99c414b8",
        "db8cda9a-b91e-4aaa-b9fe-1d175d656fec",
        "f0f505d5-95cb-4ee0-985e-1f71d11d807b"
      ],
      "position": [
        0,
        0,
        0
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "4f8c80d2-a056-45da-abd0-79e6956db51d": {
      "name": "Bounce",
      "tags": [
        "BouncePad"
      ],
      "enabled": true,
      "resource_id": "4f8c80d2-a056-45da-abd0-79e6956db51d",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        60.858726501464844,
        0.39114561676979065,
        8.117319061673555
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.9,
        2.817224769653252,
        2.9
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 29932663,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        },
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2.9,
            0.45,
            2.9
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "317a1d13-b11c-4f26-bede-e4324b7cf98a": {
      "name": "SpawnPoints",
      "tags": [],
      "enabled": true,
      "resource_id": "317a1d13-b11c-4f26-bede-e4324b7cf98a",
      "parent": "a84eb64b-ae5c-49f9-bb7c-a0746aae0286",
      "children": [
        "0540b593-f2c2-4060-ada2-2c4972d2ec8f",
        "5a9b6c3c-8fbb-425b-b53d-5f418a6f85c8",
        "5016f240-27a2-4b68-9763-2baccca107e8",
        "6c2a610d-21bd-4a6f-aeb0-1ac89b9a9a33",
        "673aeddc-4d73-42e5-b7ff-e33e700d497b",
        "f59830c7-c246-4657-9a1d-d7ebbace4a49",
        "64c05253-b842-48ab-9c4b-6d37b05f5931",
        "70a980d1-928d-4c57-b671-a79edb19247b",
        "c83f51d1-afb1-4dd1-8dae-2434f29f67a9",
        "eb73b0c1-6544-4c49-845f-6bdbe8aed68c",
        "947d0d94-e323-4b7e-ad79-e1ee14390c05",
        "36c9364f-99eb-4a82-a57d-bd8affecb8be"
      ],
      "position": [
        0,
        0,
        0
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "0540b593-f2c2-4060-ada2-2c4972d2ec8f": {
      "name": "red",
      "tags": [
        "SpawnPoint"
      ],
      "enabled": true,
      "resource_id": "0540b593-f2c2-4060-ada2-2c4972d2ec8f",
      "parent": "317a1d13-b11c-4f26-bede-e4324b7cf98a",
      "children": [],
      "position": [
        62.43052152772695,
        2.8923873901367188,
        18.047136306762695
      ],
      "rotation": [
        180,
        41.27565762121555,
        180
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "5a9b6c3c-8fbb-425b-b53d-5f418a6f85c8": {
      "name": "red",
      "tags": [
        "SpawnPoint"
      ],
      "enabled": true,
      "resource_id": "5a9b6c3c-8fbb-425b-b53d-5f418a6f85c8",
      "parent": "317a1d13-b11c-4f26-bede-e4324b7cf98a",
      "children": [],
      "position": [
        0.5816925432711324,
        3.6927597522735596,
        -26.364093780517578
      ],
      "rotation": [
        180,
        47.73779571030651,
        180
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "f59830c7-c246-4657-9a1d-d7ebbace4a49": {
      "name": "blue",
      "tags": [
        "SpawnPoint"
      ],
      "enabled": true,
      "resource_id": "f59830c7-c246-4657-9a1d-d7ebbace4a49",
      "parent": "317a1d13-b11c-4f26-bede-e4324b7cf98a",
      "children": [],
      "position": [
        70.73514011218728,
        18.090232849121094,
        -7.319929599761963
      ],
      "rotation": [
        0,
        89.00561208665917,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "5016f240-27a2-4b68-9763-2baccca107e8": {
      "name": "red",
      "tags": [
        "SpawnPoint"
      ],
      "enabled": true,
      "resource_id": "5016f240-27a2-4b68-9763-2baccca107e8",
      "parent": "317a1d13-b11c-4f26-bede-e4324b7cf98a",
      "children": [],
      "position": [
        31.96746703621082,
        3.6927597522735596,
        9.522931098937988
      ],
      "rotation": [
        0,
        69.46606834344551,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "d1011fa8-b4e4-4675-98f1-63884dd849a6": {
      "name": "hallway_1",
      "tags": [],
      "enabled": true,
      "resource_id": "d1011fa8-b4e4-4675-98f1-63884dd849a6",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "270c9100-3f7d-4a9d-9a51-8c8d780c3b2b",
        "70820481-68d0-49c7-b0e2-1cd77f2d1a40",
        "e4705144-412c-410a-b1f4-b93d3996f1e6",
        "198e10d0-6868-41e0-83bc-833cefadf396"
      ],
      "position": [
        21.965139017401338,
        -1.3653812408447266,
        -28.178074234461096
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.899112094338016,
        2.861579718525523,
        3.407250847104039
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30929888,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "270c9100-3f7d-4a9d-9a51-8c8d780c3b2b": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "270c9100-3f7d-4a9d-9a51-8c8d780c3b2b",
      "parent": "d1011fa8-b4e4-4675-98f1-63884dd849a6",
      "children": [],
      "position": [
        2.5,
        2.3307621231260267,
        -4.690684887643803e-16
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            1.7,
            6,
            10.8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "70820481-68d0-49c7-b0e2-1cd77f2d1a40": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "70820481-68d0-49c7-b0e2-1cd77f2d1a40",
      "parent": "d1011fa8-b4e4-4675-98f1-63884dd849a6",
      "children": [],
      "position": [
        -2.5,
        2.3307621675776886,
        4.809175992132244e-16
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            1.7,
            6,
            10.8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "4aa495c4-0f75-4dc9-be2d-db79e57efb4a": {
      "name": "hallway_1",
      "tags": [],
      "enabled": true,
      "resource_id": "4aa495c4-0f75-4dc9-be2d-db79e57efb4a",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "7e96654d-1dab-481a-94fe-3ae3e690aceb",
        "22fcaf45-bbfd-4cda-9d1b-49fe17b2343f",
        "801248bc-c1ba-4691-a3e4-c37e0ac9a009",
        "8d6fe6bf-28dc-4498-9f73-cdd99e82f06c"
      ],
      "position": [
        40,
        -1.3653812408447266,
        25
      ],
      "rotation": [
        0,
        90,
        0
      ],
      "scale": [
        2.899112094338016,
        2.861579718525523,
        3.407250847104039
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30929888,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "7e96654d-1dab-481a-94fe-3ae3e690aceb": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "7e96654d-1dab-481a-94fe-3ae3e690aceb",
      "parent": "4aa495c4-0f75-4dc9-be2d-db79e57efb4a",
      "children": [],
      "position": [
        2.5,
        2.3307621231260267,
        -4.690684887643803e-16
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            1.7,
            6,
            10.8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "22fcaf45-bbfd-4cda-9d1b-49fe17b2343f": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "22fcaf45-bbfd-4cda-9d1b-49fe17b2343f",
      "parent": "4aa495c4-0f75-4dc9-be2d-db79e57efb4a",
      "children": [],
      "position": [
        -2.5,
        2.3307621675776886,
        4.809175992132244e-16
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            1.7,
            6,
            10.8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "e682fb41-9409-4d68-80d3-2fce988b2359": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "e682fb41-9409-4d68-80d3-2fce988b2359",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "ffcad588-04d3-40b5-a3d3-6df0206bd208"
      ],
      "position": [
        38.939247131347656,
        0,
        -2.586890029210039
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "ffcad588-04d3-40b5-a3d3-6df0206bd208": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "ffcad588-04d3-40b5-a3d3-6df0206bd208",
      "parent": "e682fb41-9409-4d68-80d3-2fce988b2359",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "cb671089-5c1c-4779-9408-796f9f3d74c8": {
      "name": "pyramid_large",
      "tags": [],
      "enabled": true,
      "resource_id": "cb671089-5c1c-4779-9408-796f9f3d74c8",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -125.45918225563548,
        0,
        204.04916159702162
      ],
      "rotation": [
        180,
        90,
        180
      ],
      "scale": [
        10.485894782745403,
        10.485894782745403,
        10.485894782745403
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536015,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "0277d182-89fa-460f-ba0a-24a021fdfec1": {
      "name": "pyramid_large",
      "tags": [],
      "enabled": true,
      "resource_id": "0277d182-89fa-460f-ba0a-24a021fdfec1",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        326.8009338378906,
        0,
        319.91168286281055
      ],
      "rotation": [
        180,
        9.206772951298667,
        180
      ],
      "scale": [
        21.752873658996137,
        21.752873658996137,
        21.752873658996137
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536015,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100006
        }
      }
    },
    "3f449c69-6fa7-40bd-ac85-e5e0455255ce": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "3f449c69-6fa7-40bd-ac85-e5e0455255ce",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "c1200361-6702-453e-9d3c-801c5d4b38fd"
      ],
      "position": [
        33.9522356401032,
        0,
        -14.271789815135453
      ],
      "rotation": [
        0,
        -45,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "c1200361-6702-453e-9d3c-801c5d4b38fd": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "c1200361-6702-453e-9d3c-801c5d4b38fd",
      "parent": "3f449c69-6fa7-40bd-ac85-e5e0455255ce",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "9d70669a-9faf-45c9-a579-151c5aa31bee": {
      "name": "pillar_round_floor_red",
      "tags": [],
      "enabled": true,
      "resource_id": "9d70669a-9faf-45c9-a579-151c5aa31bee",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "bbfe0dcd-6f54-4b4d-9626-d8516d5223dd"
      ],
      "position": [
        -9.748470724640214,
        0,
        -31.476015219261367
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.2106873323164495,
        2.4467209881679985,
        3.2106873323164495
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30844156,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "bbfe0dcd-6f54-4b4d-9626-d8516d5223dd": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "bbfe0dcd-6f54-4b4d-9626-d8516d5223dd",
      "parent": "9d70669a-9faf-45c9-a579-151c5aa31bee",
      "children": [],
      "position": [
        5.662551139096195e-8,
        2.195946879445093,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "cylinder",
          "halfExtents": [
            1.51,
            1.51,
            1.51
          ],
          "radius": 2.2,
          "axis": 1,
          "height": 15,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "a88481a9-cd7e-481a-b270-ea665125f8f8": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "a88481a9-cd7e-481a-b270-ea665125f8f8",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        30.06229732215678,
        15.849803924560547,
        -25.655832290649414
      ],
      "rotation": [
        180,
        53.512283321197664,
        180
      ],
      "scale": [
        3.557592561989419,
        3.557592561989419,
        3.557592561989419
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "bf988d9a-e37e-494e-9b64-43549d326319": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "bf988d9a-e37e-494e-9b64-43549d326319",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "9e4aacee-d13e-41dc-82f8-afa278ee8653"
      ],
      "position": [
        -4.1418994369163356,
        0,
        -37.101745901149286
      ],
      "rotation": [
        0,
        28.8924516708616,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "9e4aacee-d13e-41dc-82f8-afa278ee8653": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "9e4aacee-d13e-41dc-82f8-afa278ee8653",
      "parent": "bf988d9a-e37e-494e-9b64-43549d326319",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "945965f7-d1f7-43b9-b272-897112b6d19f": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "945965f7-d1f7-43b9-b272-897112b6d19f",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "7f677fef-5262-4bab-b90b-bba93001264b"
      ],
      "position": [
        8.04980871809592,
        0,
        -39.992806892479486
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "7f677fef-5262-4bab-b90b-bba93001264b": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "7f677fef-5262-4bab-b90b-bba93001264b",
      "parent": "945965f7-d1f7-43b9-b272-897112b6d19f",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "a54ab68b-baa0-4131-a4b6-2d7e44a0a3ec": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "a54ab68b-baa0-4131-a4b6-2d7e44a0a3ec",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "fd762f7a-a566-46c2-b60d-16022314bf1f"
      ],
      "position": [
        -13.175606796736226,
        0,
        -23.924160658627933
      ],
      "rotation": [
        0,
        90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "fd762f7a-a566-46c2-b60d-16022314bf1f": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "fd762f7a-a566-46c2-b60d-16022314bf1f",
      "parent": "a54ab68b-baa0-4131-a4b6-2d7e44a0a3ec",
      "children": [],
      "position": [
        1.215256914005293,
        3.7020483688767527,
        8.591107389932517e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            10,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "34bc34f4-408f-41b9-aebd-863cbfb8fad1": {
      "name": "arch_1_shade_1",
      "tags": [],
      "enabled": true,
      "resource_id": "34bc34f4-408f-41b9-aebd-863cbfb8fad1",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "e3917e02-315b-47cd-9e83-42b5ab6a10d3",
        "d9303222-12f6-434e-b561-6cfe00cb079e",
        "6443e6ee-c3a3-462a-b7fb-77b791f68f61"
      ],
      "position": [
        -14.237762394033771,
        -3.844043756861092,
        -8.253822337872537
      ],
      "rotation": [
        180,
        90,
        180
      ],
      "scale": [
        7.525091683243699,
        7.686463391639226,
        6.185641263332534
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018389,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "08fe5ace-019a-434d-86f6-6a47b31129f8": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "08fe5ace-019a-434d-86f6-6a47b31129f8",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "78029918-5170-4d46-8aba-6578556cde93"
      ],
      "position": [
        -13.175606796736231,
        0,
        7.72227500284006
      ],
      "rotation": [
        0,
        90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "78029918-5170-4d46-8aba-6578556cde93": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "78029918-5170-4d46-8aba-6578556cde93",
      "parent": "08fe5ace-019a-434d-86f6-6a47b31129f8",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "eda0223f-601e-4fdc-a944-37943bb2ac7f": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "eda0223f-601e-4fdc-a944-37943bb2ac7f",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "7f86fea9-196a-4be1-877b-98f58d6b6917"
      ],
      "position": [
        -9.017732724714492,
        0,
        19.087706502425842
      ],
      "rotation": [
        180,
        50.96987627921817,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "7f86fea9-196a-4be1-877b-98f58d6b6917": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "7f86fea9-196a-4be1-877b-98f58d6b6917",
      "parent": "eda0223f-601e-4fdc-a944-37943bb2ac7f",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "906d4a5b-61d6-44ac-99e3-37e95caaa401": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "906d4a5b-61d6-44ac-99e3-37e95caaa401",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "7f089023-065d-49b8-b01e-619fcd1f5238"
      ],
      "position": [
        0.046506163255431526,
        -8.474624335925325e-16,
        26.799549132898413
      ],
      "rotation": [
        180,
        27.761704673102845,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "7f089023-065d-49b8-b01e-619fcd1f5238": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "7f089023-065d-49b8-b01e-619fcd1f5238",
      "parent": "906d4a5b-61d6-44ac-99e3-37e95caaa401",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "1af0f234-ea46-4865-ae94-05e041e8c114": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "1af0f234-ea46-4865-ae94-05e041e8c114",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "7a221a00-642e-4ccb-aa15-ef2a197b6da1"
      ],
      "position": [
        23.998952501430203,
        -3.5011304004695676e-15,
        34.44491172856479
      ],
      "rotation": [
        180,
        0,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "7a221a00-642e-4ccb-aa15-ef2a197b6da1": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "7a221a00-642e-4ccb-aa15-ef2a197b6da1",
      "parent": "1af0f234-ea46-4865-ae94-05e041e8c114",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "e16eb3cd-0ab4-4d6a-8c01-1107e97192e0": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "e16eb3cd-0ab4-4d6a-8c01-1107e97192e0",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "a6d79285-f334-43b0-8efa-7fd42e539f2b"
      ],
      "position": [
        11.50388544638558,
        -2.165663994021755e-15,
        32.04690599997796
      ],
      "rotation": [
        180,
        21.122737034927745,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "a6d79285-f334-43b0-8efa-7fd42e539f2b": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "a6d79285-f334-43b0-8efa-7fd42e539f2b",
      "parent": "e16eb3cd-0ab4-4d6a-8c01-1107e97192e0",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "c5b1b8eb-9a41-47c5-aeda-9d62a7b996a8": {
      "name": "pillar_round_floor_red",
      "tags": [],
      "enabled": true,
      "resource_id": "c5b1b8eb-9a41-47c5-aeda-9d62a7b996a8",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "39375fcc-2c3b-4992-947b-496df15a5e7c"
      ],
      "position": [
        -4.242939646811063,
        0,
        21.970865366770813
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.2106873323164495,
        2.4467209881679985,
        3.2106873323164495
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30844156,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "39375fcc-2c3b-4992-947b-496df15a5e7c": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "39375fcc-2c3b-4992-947b-496df15a5e7c",
      "parent": "c5b1b8eb-9a41-47c5-aeda-9d62a7b996a8",
      "children": [],
      "position": [
        5.662551139096195e-8,
        2.195946879445093,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "cylinder",
          "halfExtents": [
            1.51,
            1.51,
            1.51
          ],
          "radius": 2.2,
          "axis": 1,
          "height": 15,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "87b7237b-f4ad-4f52-9b3f-550cd085f7a5": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "87b7237b-f4ad-4f52-9b3f-550cd085f7a5",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "23de5c52-9d2a-4ad6-a35d-4b0c625a9d5e"
      ],
      "position": [
        24.12470773505546,
        0,
        30.32261187465774
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 29700044,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "4885fd6b-f097-4d96-9cf4-d8efbb0b8c64": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "4885fd6b-f097-4d96-9cf4-d8efbb0b8c64",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "3e069ffd-b7b0-44cd-8ab2-2d600eff274e"
      ],
      "position": [
        26.05457767494435,
        0,
        16.8822089674688
      ],
      "rotation": [
        0,
        -28.789413447115834,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018396,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "3e069ffd-b7b0-44cd-8ab2-2d600eff274e": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "3e069ffd-b7b0-44cd-8ab2-2d600eff274e",
      "parent": "4885fd6b-f097-4d96-9cf4-d8efbb0b8c64",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "06d9302d-2543-49ad-b524-173b3bd48276": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "06d9302d-2543-49ad-b524-173b3bd48276",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "44833f2d-85dc-4bde-b82f-5824b34e1595"
      ],
      "position": [
        12.362505844666671,
        0,
        4.754814147949219
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197285,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "44833f2d-85dc-4bde-b82f-5824b34e1595": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "44833f2d-85dc-4bde-b82f-5824b34e1595",
      "parent": "06d9302d-2543-49ad-b524-173b3bd48276",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "268f55b0-5cb9-49b9-9156-f0c2ecf682c6": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "268f55b0-5cb9-49b9-9156-f0c2ecf682c6",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -2.361218667739619,
        7.925600528717041,
        30.86550521850586
      ],
      "rotation": [
        0,
        12.241959690778517,
        0
      ],
      "scale": [
        3.557592561989419,
        3.557592561989419,
        3.557592561989419
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "541437fe-e87b-4e4b-b5bd-2b120c9f2f5b": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "541437fe-e87b-4e4b-b5bd-2b120c9f2f5b",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "da357917-9970-47c9-a29a-6aac00f3c04d"
      ],
      "position": [
        51.58736038208008,
        11.90999984741211,
        -7.161457538604736
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "da357917-9970-47c9-a29a-6aac00f3c04d": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel",
        "Concrete"
      ],
      "enabled": true,
      "resource_id": "da357917-9970-47c9-a29a-6aac00f3c04d",
      "parent": "541437fe-e87b-4e4b-b5bd-2b120c9f2f5b",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "f9131c11-3f56-4753-b1e4-159fbc9a0e36": {
      "name": "pillar_round_floor_red",
      "tags": [],
      "enabled": true,
      "resource_id": "f9131c11-3f56-4753-b1e4-159fbc9a0e36",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "d4244936-d6fc-4418-ad89-d2be4627c92d"
      ],
      "position": [
        44.682554360315265,
        14.225613173341465,
        -1.204647183418274
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.141443934523347,
        2.27762845224073,
        2.141443934523347
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30844156,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "d4244936-d6fc-4418-ad89-d2be4627c92d": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "d4244936-d6fc-4418-ad89-d2be4627c92d",
      "parent": "f9131c11-3f56-4753-b1e4-159fbc9a0e36",
      "children": [],
      "position": [
        5.662551139096195e-8,
        2.195946879445093,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "cylinder",
          "halfExtents": [
            1.51,
            1.51,
            1.51
          ],
          "radius": 1.6,
          "axis": 1,
          "height": 10.5,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "5c85c78a-fc22-41a3-9b69-9229c24d954d": {
      "name": "ramp_straight_shade_4",
      "tags": [],
      "enabled": true,
      "resource_id": "5c85c78a-fc22-41a3-9b69-9229c24d954d",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "27b62156-2c1d-473c-841f-fa18e10c6feb"
      ],
      "position": [
        39.8317985534668,
        9.615044593811035,
        -0.3985718786716461
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        4.7374174024643665,
        4.7374174024643665,
        4.7374174024643665
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30028242,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "27b62156-2c1d-473c-841f-fa18e10c6feb": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "27b62156-2c1d-473c-841f-fa18e10c6feb",
      "parent": "5c85c78a-fc22-41a3-9b69-9229c24d954d",
      "children": [],
      "position": [
        5.662551141252803e-8,
        0.26054600840652425,
        -0.11141224961764228
      ],
      "rotation": [
        44.90131493372405,
        -1.1273852673265173e-15,
        4.635713606664996e-15
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            20,
            1.18,
            3.65
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "df0f89e3-11b7-43ca-8a2c-d544e028e819": {
      "name": "ramp_straight_shade_4",
      "tags": [],
      "enabled": true,
      "resource_id": "df0f89e3-11b7-43ca-8a2c-d544e028e819",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [],
      "position": [
        39.8317985534668,
        9.615044593811035,
        -11.119656562805176
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        16.60316976252784,
        4.7374174024643665,
        4.7374174024643665
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30028242,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "d287fc94-a957-4b38-a884-a9b9156a885f": {
      "name": "pillar_round_floor_red",
      "tags": [],
      "enabled": true,
      "resource_id": "d287fc94-a957-4b38-a884-a9b9156a885f",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "e7aef994-a848-4864-bc82-467e8c921c98"
      ],
      "position": [
        44.61039733886719,
        14.225613594055176,
        -11.609748840332031
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.141443934523347,
        2.27762845224073,
        2.141443934523347
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30844156,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "e7aef994-a848-4864-bc82-467e8c921c98": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "e7aef994-a848-4864-bc82-467e8c921c98",
      "parent": "d287fc94-a957-4b38-a884-a9b9156a885f",
      "children": [],
      "position": [
        5.662551139096195e-8,
        2.195946879445093,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "cylinder",
          "halfExtents": [
            1.51,
            1.51,
            1.51
          ],
          "radius": 1.6,
          "axis": 1,
          "height": 10.5,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "196ad0e8-260e-43cd-af2d-341831820c9a": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "196ad0e8-260e-43cd-af2d-341831820c9a",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "6c595b3c-29a1-44a3-a606-68ee271aa9db"
      ],
      "position": [
        51.58736038208008,
        11.90999984741211,
        -26.046262741088867
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "6c595b3c-29a1-44a3-a606-68ee271aa9db": {
      "name": "Collision2",
      "tags": [
        "Rigidbody",
        "Concrete"
      ],
      "enabled": true,
      "resource_id": "6c595b3c-29a1-44a3-a606-68ee271aa9db",
      "parent": "196ad0e8-260e-43cd-af2d-341831820c9a",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0
        }
      }
    },
    "a6b57d5a-1f5c-4bff-865c-ca688bee3088": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "a6b57d5a-1f5c-4bff-865c-ca688bee3088",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "0ea26a1b-c5b8-465a-8ea3-5454a8aea4dc"
      ],
      "position": [
        42.10061264038086,
        4.609103679656982,
        -31.52943992614746
      ],
      "rotation": [
        0,
        44.0000012852106,
        0
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "23b8612f-7051-461e-aa00-79d26fb90e29": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "23b8612f-7051-461e-aa00-79d26fb90e29",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "09e5f6ba-acb2-4262-a4ed-756476f2c59f"
      ],
      "position": [
        46.832481384277344,
        4.609103679656982,
        -0.7046934962272644
      ],
      "rotation": [
        -180,
        -1.539493938844084e-38,
        -180
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "a2a4b7b8-657d-482c-9bb7-74781ac6b163": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "a2a4b7b8-657d-482c-9bb7-74781ac6b163",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "15073251-ea7c-4f5b-8056-7e729353edca"
      ],
      "position": [
        74.47208404541016,
        4.609103679656982,
        -0.7046934962272644
      ],
      "rotation": [
        -180,
        -1.539493938844084e-38,
        -180
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "5ad2affc-8a6c-40d6-a59d-39dd726664bf": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "5ad2affc-8a6c-40d6-a59d-39dd726664bf",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "d9a768ef-b026-4f09-8686-3eaee202535b"
      ],
      "position": [
        70.4404296875,
        11.90999984741211,
        -7.161457538604736
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "d9a768ef-b026-4f09-8686-3eaee202535b": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel",
        "Concrete"
      ],
      "enabled": true,
      "resource_id": "d9a768ef-b026-4f09-8686-3eaee202535b",
      "parent": "5ad2affc-8a6c-40d6-a59d-39dd726664bf",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "5a942138-e9ba-402b-a241-e873bb4945f7": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "5a942138-e9ba-402b-a241-e873bb4945f7",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "3809b374-47a7-4f05-be5a-61134e5548b0"
      ],
      "position": [
        76.89762878417969,
        4.609103679656982,
        -5.493612766265869
      ],
      "rotation": [
        6.490714038905489e-15,
        -90,
        0
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "ab887808-c837-40d1-b6fc-2b53554a2eaf": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "ab887808-c837-40d1-b6fc-2b53554a2eaf",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "73892170-ff35-4fd1-9527-ff0c253534bd"
      ],
      "position": [
        76.89762878417969,
        4.609103679656982,
        -15.030766487121582
      ],
      "rotation": [
        6.490714038905489e-15,
        -90,
        0
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "c9a0b842-3a64-4970-bd60-6e92abfc0333": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "c9a0b842-3a64-4970-bd60-6e92abfc0333",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "4170c785-222f-4837-a4d7-f1799f805575"
      ],
      "position": [
        74.16320037841797,
        4.609103679656982,
        -15.030766487121582
      ],
      "rotation": [
        -7.176245110003047e-30,
        4.0647806241547295e-46,
        6.490714038905497e-15
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "9805a7d4-838f-4887-b1b6-809f59d904ef": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "9805a7d4-838f-4887-b1b6-809f59d904ef",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "b3fccbaa-8fde-48c1-9da4-1f068f79a6d9"
      ],
      "position": [
        65.02243041992188,
        4.609103679656982,
        -15.030766487121582
      ],
      "rotation": [
        -7.176245110003047e-30,
        4.0647806241547295e-46,
        6.490714038905497e-15
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "6dca7e7d-65ba-4f5c-8a81-6323f517578d": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "6dca7e7d-65ba-4f5c-8a81-6323f517578d",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "27926157-99b4-49a3-8751-21c6d9c2ac4a"
      ],
      "position": [
        59.722381591796875,
        4.609103679656982,
        -19.824811935424805
      ],
      "rotation": [
        6.490714038905496e-15,
        -90,
        0
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "e4579fbe-05bb-4755-95cc-840ac850ad2e": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "e4579fbe-05bb-4755-95cc-840ac850ad2e",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "8ed6a5d2-f397-4ede-91cf-0e325612a617"
      ],
      "position": [
        59.722381591796875,
        4.609103679656982,
        -29.277082443237305
      ],
      "rotation": [
        6.490714038905496e-15,
        -90,
        0
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "8495f353-d6f2-4b63-bd87-991908ad65f3": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "8495f353-d6f2-4b63-bd87-991908ad65f3",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "ea79a57b-01db-4003-af29-a9786568848b",
        "3a4dcdae-0818-45a0-a53d-281c5b37aa05"
      ],
      "position": [
        51.49159622192383,
        23.96975326538086,
        -7.237765312194824
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "ea79a57b-01db-4003-af29-a9786568848b": {
      "name": "Collision",
      "tags": [
        "Invisible"
      ],
      "enabled": true,
      "resource_id": "ea79a57b-01db-4003-af29-a9786568848b",
      "parent": "8495f353-d6f2-4b63-bd87-991908ad65f3",
      "children": [],
      "position": [
        3.840559530754028,
        3.998767320572938,
        8.703393348241661e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            18.247,
            7,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "e5556b97-2ac5-441a-a483-0f35a75288f0": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "e5556b97-2ac5-441a-a483-0f35a75288f0",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "ed390bea-32fd-4ea5-b525-d34066a872a2"
      ],
      "position": [
        51.49159622192383,
        23.96975326538086,
        -25.943429946899414
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "ed390bea-32fd-4ea5-b525-d34066a872a2": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "ed390bea-32fd-4ea5-b525-d34066a872a2",
      "parent": "e5556b97-2ac5-441a-a483-0f35a75288f0",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "9b73994b-88d8-4dc0-b698-0ed577bf0a1f": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "9b73994b-88d8-4dc0-b698-0ed577bf0a1f",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "548094b2-afa2-450d-83e9-0073a7975c90"
      ],
      "position": [
        70.35665893554688,
        23.96975326538086,
        -7.237765312194824
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "548094b2-afa2-450d-83e9-0073a7975c90": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel",
        "Grapple"
      ],
      "enabled": true,
      "resource_id": "548094b2-afa2-450d-83e9-0073a7975c90",
      "parent": "9b73994b-88d8-4dc0-b698-0ed577bf0a1f",
      "children": [],
      "position": [
        -3.9908540277056765,
        0.4551903084258129,
        8.703393348241661e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            18.864,
            1.23,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "22e89aa3-90ac-4029-baa8-0b841d039fa4": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "22e89aa3-90ac-4029-baa8-0b841d039fa4",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "3d42bf03-f8e1-4c09-baee-e1964be32b8f",
        "9a332baa-42ae-4b90-b2ed-110b577ebb43"
      ],
      "position": [
        42.80849838256836,
        23.96632957458496,
        -23.661739349365234
      ],
      "rotation": [
        0,
        44.000000992470014,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "3d42bf03-f8e1-4c09-baee-e1964be32b8f": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Grapple",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "3d42bf03-f8e1-4c09-baee-e1964be32b8f",
      "parent": "22e89aa3-90ac-4029-baa8-0b841d039fa4",
      "children": [],
      "position": [
        -0.000004868831524618145,
        0.4899805702605615,
        -0.00000327543693856569
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.197,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "0fcb6d71-1066-452a-bc49-421edcfd5925": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "0fcb6d71-1066-452a-bc49-421edcfd5925",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "32f38705-494b-4a0d-b3bd-98eca7a2d9a0"
      ],
      "position": [
        35.1363410949707,
        4.609103679656982,
        -24.80412483215332
      ],
      "rotation": [
        0,
        44.0000012852106,
        0
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "1c072d8c-6383-45ca-83f6-8842b9dd6dd2": {
      "name": "ramp_straight_shade_4",
      "tags": [],
      "enabled": true,
      "resource_id": "1c072d8c-6383-45ca-83f6-8842b9dd6dd2",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "f3294db8-21d3-4780-baaa-9043a49135ea"
      ],
      "position": [
        34.34510803222656,
        9.615044593811035,
        -15.532028198242188
      ],
      "rotation": [
        0,
        -45.819909252991984,
        0
      ],
      "scale": [
        18.829451830543068,
        4.7374174024643665,
        4.7374174024643665
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30028242,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "f3294db8-21d3-4780-baaa-9043a49135ea": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "f3294db8-21d3-4780-baaa-9043a49135ea",
      "parent": "1c072d8c-6383-45ca-83f6-8842b9dd6dd2",
      "children": [],
      "position": [
        5.662551141252803e-8,
        0.26054600840652425,
        -0.11141224961764228
      ],
      "rotation": [
        44.90131493372405,
        -1.1273852673265173e-15,
        4.635713606664996e-15
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            8.7,
            1.18,
            3.65
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "62124c1d-223c-4d9b-b2a8-8fea7ccabca2": {
      "name": "pillar_round_floor_red",
      "tags": [],
      "enabled": true,
      "resource_id": "62124c1d-223c-4d9b-b2a8-8fea7ccabca2",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "30885c36-fc39-4d3f-bb23-6692af726209"
      ],
      "position": [
        36.84419250488281,
        14.225613594055176,
        -19.862855911254883
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.141443934523347,
        2.27762845224073,
        2.141443934523347
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30844156,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "30885c36-fc39-4d3f-bb23-6692af726209": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "30885c36-fc39-4d3f-bb23-6692af726209",
      "parent": "62124c1d-223c-4d9b-b2a8-8fea7ccabca2",
      "children": [],
      "position": [
        5.662551139096195e-8,
        2.195946879445093,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "cylinder",
          "halfExtents": [
            1.51,
            1.51,
            1.51
          ],
          "radius": 1.6,
          "axis": 1,
          "height": 10.5,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "e1a7d145-87c5-4af9-8000-91236b009fca": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "e1a7d145-87c5-4af9-8000-91236b009fca",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "893670cd-91d6-418c-b841-a5e96ca5d71f"
      ],
      "position": [
        42.80849838256836,
        11.899999618530273,
        -23.661739349365234
      ],
      "rotation": [
        0,
        -44.000000992470014,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "893670cd-91d6-418c-b841-a5e96ca5d71f": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Concrete"
      ],
      "enabled": true,
      "resource_id": "893670cd-91d6-418c-b841-a5e96ca5d71f",
      "parent": "e1a7d145-87c5-4af9-8000-91236b009fca",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            8,
            1.18,
            8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "32f38705-494b-4a0d-b3bd-98eca7a2d9a0": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "32f38705-494b-4a0d-b3bd-98eca7a2d9a0",
      "parent": "0fcb6d71-1066-452a-bc49-421edcfd5925",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "0ea26a1b-c5b8-465a-8ea3-5454a8aea4dc": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "0ea26a1b-c5b8-465a-8ea3-5454a8aea4dc",
      "parent": "a6b57d5a-1f5c-4bff-865c-ca688bee3088",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "09e5f6ba-acb2-4262-a4ed-756476f2c59f": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "09e5f6ba-acb2-4262-a4ed-756476f2c59f",
      "parent": "23b8612f-7051-461e-aa00-79d26fb90e29",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "15073251-ea7c-4f5b-8056-7e729353edca": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "15073251-ea7c-4f5b-8056-7e729353edca",
      "parent": "a2a4b7b8-657d-482c-9bb7-74781ac6b163",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "3809b374-47a7-4f05-be5a-61134e5548b0": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "3809b374-47a7-4f05-be5a-61134e5548b0",
      "parent": "5a942138-e9ba-402b-a241-e873bb4945f7",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "73892170-ff35-4fd1-9527-ff0c253534bd": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "73892170-ff35-4fd1-9527-ff0c253534bd",
      "parent": "ab887808-c837-40d1-b6fc-2b53554a2eaf",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "4170c785-222f-4837-a4d7-f1799f805575": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "4170c785-222f-4837-a4d7-f1799f805575",
      "parent": "c9a0b842-3a64-4970-bd60-6e92abfc0333",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "b3fccbaa-8fde-48c1-9da4-1f068f79a6d9": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "b3fccbaa-8fde-48c1-9da4-1f068f79a6d9",
      "parent": "9805a7d4-838f-4887-b1b6-809f59d904ef",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "27926157-99b4-49a3-8751-21c6d9c2ac4a": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "27926157-99b4-49a3-8751-21c6d9c2ac4a",
      "parent": "6dca7e7d-65ba-4f5c-8a81-6323f517578d",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "8ed6a5d2-f397-4ede-91cf-0e325612a617": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "8ed6a5d2-f397-4ede-91cf-0e325612a617",
      "parent": "e4579fbe-05bb-4755-95cc-840ac850ad2e",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "23de5c52-9d2a-4ad6-a35d-4b0c625a9d5e": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic"
      ],
      "enabled": true,
      "resource_id": "23de5c52-9d2a-4ad6-a35d-4b0c625a9d5e",
      "parent": "87b7237b-f4ad-4f52-9b3f-550cd085f7a5",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "3177ce5e-32f6-4d9e-bdef-b9a56b80d048": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "3177ce5e-32f6-4d9e-bdef-b9a56b80d048",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "6b364fbd-1cf3-440e-805b-e0a6c7d55a2f"
      ],
      "position": [
        49.491737365722656,
        -3.501130431103898e-15,
        -0.49187959233089495
      ],
      "rotation": [
        -2.5444437451708134e-14,
        3.449914803592871e-45,
        1.5537035023920813e-29
      ],
      "scale": [
        3.982600780221009,
        3.0840293312107256,
        2.9049360745341204
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "6b364fbd-1cf3-440e-805b-e0a6c7d55a2f": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "6b364fbd-1cf3-440e-805b-e0a6c7d55a2f",
      "parent": "3177ce5e-32f6-4d9e-bdef-b9a56b80d048",
      "children": [],
      "position": [
        -0.0000034340746424277313,
        1.7617526934961976,
        7.985923730635669e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            7.98,
            7,
            2.95
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "9ea8edcf-13e9-4e1e-978d-1c0243524e6d": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "9ea8edcf-13e9-4e1e-978d-1c0243524e6d",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "9d34d9dc-8119-47f1-81ee-b2fe3026b099"
      ],
      "position": [
        65.14585876464844,
        -3.501130431103898e-15,
        -0.49187959233089495
      ],
      "rotation": [
        -2.5444437451708134e-14,
        3.449914803592871e-45,
        1.5537035023920813e-29
      ],
      "scale": [
        3.982600780221009,
        3.0840293312107256,
        2.9049360745341204
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "9d34d9dc-8119-47f1-81ee-b2fe3026b099": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "9d34d9dc-8119-47f1-81ee-b2fe3026b099",
      "parent": "9ea8edcf-13e9-4e1e-978d-1c0243524e6d",
      "children": [],
      "position": [
        -0.0000034340746424277313,
        1.7617526934961976,
        7.985923730635669e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            7.98,
            7,
            2.95
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "2a679e3a-32a9-4909-8d30-f1e3175dcf7e": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "2a679e3a-32a9-4909-8d30-f1e3175dcf7e",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "3f7d50f8-50f6-4f4c-9eb4-4bbd5c6b7b2a"
      ],
      "position": [
        38.939247131347656,
        0,
        9.980771756822595
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "3f7d50f8-50f6-4f4c-9eb4-4bbd5c6b7b2a": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "3f7d50f8-50f6-4f4c-9eb4-4bbd5c6b7b2a",
      "parent": "2a679e3a-32a9-4909-8d30-f1e3175dcf7e",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "fc55f80c-57f6-4ff8-a8d7-751c082ea925": {
      "name": "wall_pannel_01_shade_3",
      "tags": [],
      "enabled": true,
      "resource_id": "fc55f80c-57f6-4ff8-a8d7-751c082ea925",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "89ad7ef6-4f6b-494e-8e24-8ac3e4dcea12"
      ],
      "position": [
        41.96915054321289,
        9.5603609085083,
        5.5483662770853766
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        7.244566294022107,
        7.244566294022107,
        10.775200642972559
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30017386,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100004
        }
      }
    },
    "0ecbd550-7969-4ab7-a5e6-264f8490bd5d": {
      "name": "wall_pannel_01_shade_3",
      "tags": [],
      "enabled": true,
      "resource_id": "0ecbd550-7969-4ab7-a5e6-264f8490bd5d",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        41.96915054321289,
        9.5603609085083,
        12.270788014588026
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        6.581725378563207,
        7.244566294022107,
        10.775200642972559
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30017386,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100004
        }
      }
    },
    "3971dcee-5d63-45d9-b143-47c85dc03982": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "3971dcee-5d63-45d9-b143-47c85dc03982",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "4f8fa38d-7db6-4786-982e-d32676d29b8e"
      ],
      "position": [
        70.28915405273438,
        0,
        13.214698560584232
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018396,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "4f8fa38d-7db6-4786-982e-d32676d29b8e": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic"
      ],
      "enabled": true,
      "resource_id": "4f8fa38d-7db6-4786-982e-d32676d29b8e",
      "parent": "3971dcee-5d63-45d9-b143-47c85dc03982",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "a0e12a44-4896-4f53-b912-ee7747d047e5": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "a0e12a44-4896-4f53-b912-ee7747d047e5",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "f4dcc147-3369-4d41-a328-e56554d0b5f0"
      ],
      "position": [
        75.27461242675781,
        -3.501130431103898e-15,
        9.808632850646973
      ],
      "rotation": [
        -2.5444437451708134e-14,
        -90,
        0
      ],
      "scale": [
        3.982600780221009,
        3.0840293312107256,
        2.9049360745341204
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "f4dcc147-3369-4d41-a328-e56554d0b5f0": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "f4dcc147-3369-4d41-a328-e56554d0b5f0",
      "parent": "a0e12a44-4896-4f53-b912-ee7747d047e5",
      "children": [],
      "position": [
        0.4940957728984925,
        3.9764681558284005,
        8.102643178631297e-8
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            10,
            15,
            2.95
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "233162ac-3c42-4358-900e-67721eba3ddf": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "233162ac-3c42-4358-900e-67721eba3ddf",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "d6c47f83-669b-4b77-ab5a-e93070b995d9"
      ],
      "position": [
        71.09789276123047,
        -3.501130431103898e-15,
        25.607473373413086
      ],
      "rotation": [
        179.99999999999997,
        -60.93157320638009,
        180
      ],
      "scale": [
        3.982600780221009,
        3.0840293312107256,
        2.9049360745341204
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "d6c47f83-669b-4b77-ab5a-e93070b995d9": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "d6c47f83-669b-4b77-ab5a-e93070b995d9",
      "parent": "233162ac-3c42-4358-900e-67721eba3ddf",
      "children": [],
      "position": [
        -0.000004316936923487447,
        3.7452159799966855,
        0.0000013668854172976808
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            7.98,
            14.078,
            2.95
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "01abeffc-f2f3-4447-b48c-e9d58c318350": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "01abeffc-f2f3-4447-b48c-e9d58c318350",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "c9ebc114-28ac-4a84-bda1-2c956f4671de"
      ],
      "position": [
        58.436756001235345,
        -3.107325646245957e-15,
        33.035132637945175
      ],
      "rotation": [
        179.99999999999997,
        -11.853686390823295,
        180
      ],
      "scale": [
        3.982600780221009,
        3.0840293312107256,
        2.9049360745341204
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "c9ebc114-28ac-4a84-bda1-2c956f4671de": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "c9ebc114-28ac-4a84-bda1-2c956f4671de",
      "parent": "01abeffc-f2f3-4447-b48c-e9d58c318350",
      "children": [],
      "position": [
        -0.0000029717141813989656,
        3.869059366723523,
        4.0197619810555807e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            7.98,
            15.502,
            2.95
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "89ad7ef6-4f6b-494e-8e24-8ac3e4dcea12": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "89ad7ef6-4f6b-494e-8e24-8ac3e4dcea12",
      "parent": "fc55f80c-57f6-4ff8-a8d7-751c082ea925",
      "children": [],
      "position": [
        0.5965633725525943,
        0.6104287609235107,
        0.1310573669132799
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            8,
            5,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "d9303222-12f6-434e-b561-6cfe00cb079e": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "d9303222-12f6-434e-b561-6cfe00cb079e",
      "parent": "34bc34f4-408f-41b9-aebd-863cbfb8fad1",
      "children": [],
      "position": [
        0.9970445319995354,
        1.7829515249140595,
        -0.006462223699827074
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2.8,
            10,
            2.22
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "6443e6ee-c3a3-462a-b7fb-77b791f68f61": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "6443e6ee-c3a3-462a-b7fb-77b791f68f61",
      "parent": "34bc34f4-408f-41b9-aebd-863cbfb8fad1",
      "children": [],
      "position": [
        -0.9998505457887057,
        1.7761757763179902,
        -0.006462223699827518
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2.8,
            10,
            2.22
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "5729286f-f54d-477e-b03c-3c6a44d8dc5e": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "5729286f-f54d-477e-b03c-3c6a44d8dc5e",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "8e3c871b-8b12-4071-a72e-9b4128839dee"
      ],
      "position": [
        51.58736038208008,
        11.90999984741211,
        -44.8515625
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "8e3c871b-8b12-4071-a72e-9b4128839dee": {
      "name": "Collision2",
      "tags": [
        "Rigidbody",
        "Concrete"
      ],
      "enabled": true,
      "resource_id": "8e3c871b-8b12-4071-a72e-9b4128839dee",
      "parent": "5729286f-f54d-477e-b03c-3c6a44d8dc5e",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0
        }
      }
    },
    "fa37361c-854c-49b8-ac7b-0567199cf43e": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "fa37361c-854c-49b8-ac7b-0567199cf43e",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "be1b97af-d8c9-48b9-bb15-79c15e5eeb98"
      ],
      "position": [
        59.722381591796875,
        4.609103679656982,
        -38.81599426269531
      ],
      "rotation": [
        6.490714038905496e-15,
        -90,
        0
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "be1b97af-d8c9-48b9-bb15-79c15e5eeb98": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "be1b97af-d8c9-48b9-bb15-79c15e5eeb98",
      "parent": "fa37361c-854c-49b8-ac7b-0567199cf43e",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "392067cc-b07a-4041-9458-91943dbf7361": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "392067cc-b07a-4041-9458-91943dbf7361",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "52b2c4e3-75e9-4d1b-8196-b7be5aa78279"
      ],
      "position": [
        57.260955810546875,
        4.609103679656982,
        -46.703182220458984
      ],
      "rotation": [
        3.94347681867677e-23,
        -54.23608302574899,
        6.4907138120683975e-15
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "52b2c4e3-75e9-4d1b-8196-b7be5aa78279": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "52b2c4e3-75e9-4d1b-8196-b7be5aa78279",
      "parent": "392067cc-b07a-4041-9458-91943dbf7361",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "a1be1753-8330-4b74-95ef-9699d1ba85f6": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "a1be1753-8330-4b74-95ef-9699d1ba85f6",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "17d89c86-d477-4402-8ac7-d3e1c1a945d7"
      ],
      "position": [
        50.38163375854492,
        4.609103679656982,
        -50.34695053100586
      ],
      "rotation": [
        1.835878950436921e-31,
        -1.039881591506334e-47,
        6.490714038905497e-15
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "17d89c86-d477-4402-8ac7-d3e1c1a945d7": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "17d89c86-d477-4402-8ac7-d3e1c1a945d7",
      "parent": "a1be1753-8330-4b74-95ef-9699d1ba85f6",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "75032b07-d344-42c0-9269-b65adfe21203": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "75032b07-d344-42c0-9269-b65adfe21203",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "c8b5238c-e7d7-454b-93fe-bf5b0b9b3ca1"
      ],
      "position": [
        41.13134002685547,
        4.609103679656982,
        -50.34695053100586
      ],
      "rotation": [
        1.835878950436921e-31,
        -1.039881591506334e-47,
        6.490714038905497e-15
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "c8b5238c-e7d7-454b-93fe-bf5b0b9b3ca1": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "c8b5238c-e7d7-454b-93fe-bf5b0b9b3ca1",
      "parent": "75032b07-d344-42c0-9269-b65adfe21203",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "bdbad0d1-f6ac-41c5-9359-c8bc6a76a04b": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "bdbad0d1-f6ac-41c5-9359-c8bc6a76a04b",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "7caf8bc2-6ad6-44be-9ebd-82d02f76234f"
      ],
      "position": [
        37.223304261110904,
        11.9,
        -44.85156138010018
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "7caf8bc2-6ad6-44be-9ebd-82d02f76234f": {
      "name": "Collision2",
      "tags": [
        "Rigidbody",
        "Concrete"
      ],
      "enabled": true,
      "resource_id": "7caf8bc2-6ad6-44be-9ebd-82d02f76234f",
      "parent": "bdbad0d1-f6ac-41c5-9359-c8bc6a76a04b",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0
        }
      }
    },
    "5530f4ef-e787-4f32-81dd-814890c9647c": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "5530f4ef-e787-4f32-81dd-814890c9647c",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "f44933fd-a367-4251-b285-87b3f8bcdbe3"
      ],
      "position": [
        32.750659229159,
        4.609103807098384,
        -50.346950624443366
      ],
      "rotation": [
        1.8358790399348976e-31,
        0,
        6.490713843471307e-15
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "f44933fd-a367-4251-b285-87b3f8bcdbe3": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "f44933fd-a367-4251-b285-87b3f8bcdbe3",
      "parent": "5530f4ef-e787-4f32-81dd-814890c9647c",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "af8d6d2c-9d79-492b-816f-e70e0e7ba470": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "af8d6d2c-9d79-492b-816f-e70e0e7ba470",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "abbbca9f-47e3-44fb-8a09-299769691feb"
      ],
      "position": [
        41.13133832610687,
        4.609103807098385,
        -35.14848194859235
      ],
      "rotation": [
        1.8358790399348976e-31,
        0,
        6.490713843471307e-15
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "abbbca9f-47e3-44fb-8a09-299769691feb": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "abbbca9f-47e3-44fb-8a09-299769691feb",
      "parent": "af8d6d2c-9d79-492b-816f-e70e0e7ba470",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "fcdbe068-1d30-4016-9b94-9374ad1e37c6": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "fcdbe068-1d30-4016-9b94-9374ad1e37c6",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "6a5dc72a-da6a-4ce3-af5f-360da46ee901"
      ],
      "position": [
        32.965655057449226,
        4.609103807098384,
        -35.14848194859235
      ],
      "rotation": [
        1.8358790399348976e-31,
        0,
        6.490713843471307e-15
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "6a5dc72a-da6a-4ce3-af5f-360da46ee901": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "6a5dc72a-da6a-4ce3-af5f-360da46ee901",
      "parent": "fcdbe068-1d30-4016-9b94-9374ad1e37c6",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "a7a69edc-7c03-4f1d-8152-97702cdebb25": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "a7a69edc-7c03-4f1d-8152-97702cdebb25",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "63de675f-5ac0-4d85-8ddb-5641102ab15c"
      ],
      "position": [
        31.72353947221936,
        1.583943114539951e-14,
        -46.0187789035452
      ],
      "rotation": [
        -2.5444437451708178e-14,
        -90,
        4.675085598633209e-29
      ],
      "scale": [
        3.982600780221009,
        3.0840293312107256,
        2.9049360745341204
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "63de675f-5ac0-4d85-8ddb-5641102ab15c": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "63de675f-5ac0-4d85-8ddb-5641102ab15c",
      "parent": "a7a69edc-7c03-4f1d-8152-97702cdebb25",
      "children": [],
      "position": [
        -0.0000034340746424277313,
        1.7617526934961976,
        7.985923730635669e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            7.98,
            7,
            2.95
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "6bc339cd-81a0-4470-939c-9a17c1250510": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "6bc339cd-81a0-4470-939c-9a17c1250510",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "b4ba5cdd-15ea-4921-80f6-eee406abab08"
      ],
      "position": [
        21.15624054672179,
        2.053225457547314e-14,
        -54.69011045752707
      ],
      "rotation": [
        -3.074053880907575e-30,
        0,
        -2.5444437451708125e-14
      ],
      "scale": [
        3.982600780221009,
        3.0840293312107256,
        2.9049360745341204
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "b4ba5cdd-15ea-4921-80f6-eee406abab08": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "b4ba5cdd-15ea-4921-80f6-eee406abab08",
      "parent": "6bc339cd-81a0-4470-939c-9a17c1250510",
      "children": [],
      "position": [
        -0.0000034340746424277313,
        1.7617526934961976,
        7.985923730635669e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            7.98,
            7,
            2.95
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "a6c91bf8-ca37-4d1d-a08c-9b093e3717f0": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "a6c91bf8-ca37-4d1d-a08c-9b093e3717f0",
      "parent": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "children": [
        "2b9f85b5-5af0-450f-9ab5-a9e1dcc39fe0"
      ],
      "position": [
        51.49159622192383,
        23.96975326538086,
        -44.4349250793457
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "2b9f85b5-5af0-450f-9ab5-a9e1dcc39fe0": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "2b9f85b5-5af0-450f-9ab5-a9e1dcc39fe0",
      "parent": "a6c91bf8-ca37-4d1d-a08c-9b093e3717f0",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "4fe10cac-0b7e-4daa-b4f3-04604c6c478e": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "4fe10cac-0b7e-4daa-b4f3-04604c6c478e",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "f60958a1-1e8b-49a8-a3ec-217a0958784a"
      ],
      "position": [
        37.22677466293024,
        23.969754053463774,
        -44.434923735125366
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "f60958a1-1e8b-49a8-a3ec-217a0958784a": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "f60958a1-1e8b-49a8-a3ec-217a0958784a",
      "parent": "4fe10cac-0b7e-4daa-b4f3-04604c6c478e",
      "children": [],
      "position": [
        -4.490875653573312e-7,
        2.962240446334249,
        5.655869017573423e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            7,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "f9f748ae-bad1-40fb-83eb-885c2b5e422c": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "f9f748ae-bad1-40fb-83eb-885c2b5e422c",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "79ac37ed-91a1-4329-9161-c32d65d5326f"
      ],
      "position": [
        11.629373056455618,
        2.4763033631571696e-14,
        -46.53891410658248
      ],
      "rotation": [
        -2.0452776969941694e-29,
        90,
        -2.5444437451708156e-14
      ],
      "scale": [
        3.982600780221009,
        3.0840293312107256,
        2.9049360745341204
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "79ac37ed-91a1-4329-9161-c32d65d5326f": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "79ac37ed-91a1-4329-9161-c32d65d5326f",
      "parent": "f9f748ae-bad1-40fb-83eb-885c2b5e422c",
      "children": [],
      "position": [
        -0.0000034340746424277313,
        1.7617526934961976,
        7.985923730635669e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            7.98,
            7,
            2.95
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "f9573a00-b768-4783-8c5a-833467192ff9": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "f9573a00-b768-4783-8c5a-833467192ff9",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "a08dd42d-df96-4070-8efa-9657dbd78e94"
      ],
      "position": [
        44.638355976958984,
        14.284504003924198,
        -31.745588225807527
      ],
      "rotation": [
        0,
        -42.974161702400274,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018396,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "a08dd42d-df96-4070-8efa-9657dbd78e94": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic"
      ],
      "enabled": true,
      "resource_id": "a08dd42d-df96-4070-8efa-9657dbd78e94",
      "parent": "f9573a00-b768-4783-8c5a-833467192ff9",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "e0e86911-ad60-4bd2-9431-bcef58544dc4": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "e0e86911-ad60-4bd2-9431-bcef58544dc4",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "76b157bf-a669-4fa6-8368-a708d544546b"
      ],
      "position": [
        38.88548882958308,
        14.284504003924198,
        -25.570813056202468
      ],
      "rotation": [
        0,
        -42.974161702400274,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 29700044,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "76b157bf-a669-4fa6-8368-a708d544546b": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic"
      ],
      "enabled": true,
      "resource_id": "76b157bf-a669-4fa6-8368-a708d544546b",
      "parent": "e0e86911-ad60-4bd2-9431-bcef58544dc4",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "c0924f99-993b-4bbb-bf8a-a61575410ad0": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "c0924f99-993b-4bbb-bf8a-a61575410ad0",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "7a3e629d-09d3-4090-b322-3cf24983ece1"
      ],
      "position": [
        -18.221773147583008,
        0,
        7.9462913249669
      ],
      "rotation": [
        0,
        90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "7a3e629d-09d3-4090-b322-3cf24983ece1": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "7a3e629d-09d3-4090-b322-3cf24983ece1",
      "parent": "c0924f99-993b-4bbb-bf8a-a61575410ad0",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "180784ca-5ace-4e6d-879d-ba4ef9f1adb3": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "180784ca-5ace-4e6d-879d-ba4ef9f1adb3",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "f0b178e1-e5de-4c35-96cf-f47ec606ab60"
      ],
      "position": [
        -40.9193000793457,
        0.7090284897643855,
        12.162617683410645
      ],
      "rotation": [
        0,
        90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "f0b178e1-e5de-4c35-96cf-f47ec606ab60": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "f0b178e1-e5de-4c35-96cf-f47ec606ab60",
      "parent": "180784ca-5ace-4e6d-879d-ba4ef9f1adb3",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "e85d2a34-f589-4c48-8e45-2aafdfd988e4": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "e85d2a34-f589-4c48-8e45-2aafdfd988e4",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "0096b1ba-34e9-4d3a-8402-9443df731409"
      ],
      "position": [
        -18.221773147583008,
        2.2818317653037106,
        20.144014358520508
      ],
      "rotation": [
        0,
        90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "0096b1ba-34e9-4d3a-8402-9443df731409": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "0096b1ba-34e9-4d3a-8402-9443df731409",
      "parent": "e85d2a34-f589-4c48-8e45-2aafdfd988e4",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "178e75da-5e22-4320-b46c-0385ae30bcd2": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "178e75da-5e22-4320-b46c-0385ae30bcd2",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "814facef-32ea-44ef-ae6a-1606ef687f99"
      ],
      "position": [
        -41.057598495275954,
        3.6681721210479736,
        24.528648376464844
      ],
      "rotation": [
        0,
        90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "814facef-32ea-44ef-ae6a-1606ef687f99": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "814facef-32ea-44ef-ae6a-1606ef687f99",
      "parent": "178e75da-5e22-4320-b46c-0385ae30bcd2",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "f616b29e-6c81-4cfa-8203-3f2819a29414": {
      "position": [
        -0.9662908511205579,
        7.628909207801844,
        31.730180884885883
      ],
      "scale": [
        20,
        1,
        20
      ],
      "name": "Ground",
      "parent": "ed8f5360-faac-4431-975e-ba733fc8b3ff",
      "resource_id": "f616b29e-6c81-4cfa-8203-3f2819a29414",
      "components": {
        "model": {
          "layers": [
            0
          ],
          "isStatic": false,
          "castShadows": true,
          "castShadowsLightmap": false,
          "lightmapped": false,
          "materialAsset": 29542740,
          "receiveShadows": true,
          "enabled": true,
          "castShadowsLightMap": false,
          "asset": null,
          "type": "plane",
          "lightmapSizeMultiplier": 1,
          "batchGroupId": null
        },
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            10,
            0.01,
            10
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      },
      "rotation": [
        -90.00000113393138,
        -74.99999870487031,
        90.00000032354309
      ],
      "tags": [
        "Dirt"
      ],
      "enabled": true,
      "children": []
    },
    "ba866499-c617-4665-bbbf-d442a8ce8609": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "ba866499-c617-4665-bbbf-d442a8ce8609",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "57595c77-2c24-4fb4-8af3-e2169e03a7ae"
      ],
      "position": [
        -18.22177314758301,
        5.885346159140969,
        32.53864248628094
      ],
      "rotation": [
        0,
        90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "57595c77-2c24-4fb4-8af3-e2169e03a7ae": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "57595c77-2c24-4fb4-8af3-e2169e03a7ae",
      "parent": "ba866499-c617-4665-bbbf-d442a8ce8609",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "25fbd918-6a1a-4a05-9188-0ca0f2de3867": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "25fbd918-6a1a-4a05-9188-0ca0f2de3867",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "901dbd32-c57a-4ead-a186-5c20a85bbd36"
      ],
      "position": [
        -40.9193000793457,
        5.975546271206924,
        35.578633954293196
      ],
      "rotation": [
        0,
        90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "901dbd32-c57a-4ead-a186-5c20a85bbd36": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "901dbd32-c57a-4ead-a186-5c20a85bbd36",
      "parent": "25fbd918-6a1a-4a05-9188-0ca0f2de3867",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "6b75599a-ff8c-4001-9031-b57dd06fd1f6": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "6b75599a-ff8c-4001-9031-b57dd06fd1f6",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "350ddc22-97c8-4801-ac87-49b4f8293e3c"
      ],
      "position": [
        -40.9193000793457,
        9.89092941499436,
        47.972949293532025
      ],
      "rotation": [
        0,
        90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "350ddc22-97c8-4801-ac87-49b4f8293e3c": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "350ddc22-97c8-4801-ac87-49b4f8293e3c",
      "parent": "6b75599a-ff8c-4001-9031-b57dd06fd1f6",
      "children": [],
      "position": [
        5.662551139096195e-8,
        3.4961505858965745,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            9,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "8cd0a054-dbdf-46d2-8fa8-96cab7f8e260": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "8cd0a054-dbdf-46d2-8fa8-96cab7f8e260",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "54ecccf3-2a0a-4dc6-8091-416b071358cb"
      ],
      "position": [
        -33.00137045595802,
        9.890929414994357,
        56.34039148930346
      ],
      "rotation": [
        180,
        0,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "54ecccf3-2a0a-4dc6-8091-416b071358cb": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "54ecccf3-2a0a-4dc6-8091-416b071358cb",
      "parent": "8cd0a054-dbdf-46d2-8fa8-96cab7f8e260",
      "children": [],
      "position": [
        8.456174782622838e-8,
        2.9036581177207283,
        0.000001194057404063642
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "213735c7-f714-4464-960b-c1faa1cde037": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "213735c7-f714-4464-960b-c1faa1cde037",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "9f3155d7-a6c1-4e96-a03e-c5a694a5b76b"
      ],
      "position": [
        -21.09429202653185,
        9.890929414994355,
        56.34039148930346
      ],
      "rotation": [
        180,
        0,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "9f3155d7-a6c1-4e96-a03e-c5a694a5b76b": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "9f3155d7-a6c1-4e96-a03e-c5a694a5b76b",
      "parent": "213735c7-f714-4464-960b-c1faa1cde037",
      "children": [],
      "position": [
        7.358289710879262e-8,
        2.8577966887730204,
        0.000001194057404063642
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "1e2e98a5-a985-43ec-a41a-1140de21e2f3": {
      "position": [
        -9.32564240772449,
        10.2,
        51.38355570552187
      ],
      "scale": [
        20,
        1,
        20
      ],
      "name": "Ground",
      "parent": "a84eb64b-ae5c-49f9-bb7c-a0746aae0286",
      "resource_id": "1e2e98a5-a985-43ec-a41a-1140de21e2f3",
      "components": {
        "model": {
          "layers": [
            0
          ],
          "isStatic": false,
          "castShadows": true,
          "castShadowsLightmap": false,
          "lightmapped": false,
          "materialAsset": 29542740,
          "receiveShadows": true,
          "enabled": true,
          "castShadowsLightMap": false,
          "asset": null,
          "type": "plane",
          "lightmapSizeMultiplier": 1,
          "batchGroupId": null
        },
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            10,
            0.01,
            10
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      },
      "rotation": [
        0,
        0,
        0
      ],
      "tags": [
        "Dirt"
      ],
      "enabled": true,
      "children": []
    },
    "a71ce0ab-f22f-4f75-8692-547d4f72527f": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "a71ce0ab-f22f-4f75-8692-547d4f72527f",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "8346194c-c6d4-464e-b540-0e6c8726c740"
      ],
      "position": [
        -14.559963961474956,
        8.8521152731558,
        40.11875129804925
      ],
      "rotation": [
        180,
        0,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "8346194c-c6d4-464e-b540-0e6c8726c740": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "8346194c-c6d4-464e-b540-0e6c8726c740",
      "parent": "a71ce0ab-f22f-4f75-8692-547d4f72527f",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "c3b137eb-4dbb-49ca-a0da-9df7ace9c551": {
      "name": "hallway_1",
      "tags": [],
      "enabled": true,
      "resource_id": "c3b137eb-4dbb-49ca-a0da-9df7ace9c551",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "a2c8ef7a-b137-411d-b5d6-4c05fe4afb68",
        "8819a953-1f35-4d53-8582-68bcfb49e35a",
        "2254638f-a297-46ef-adf4-2fa1edc33490"
      ],
      "position": [
        -3.607505495796743,
        8.89287120562873,
        48.2880566034302
      ],
      "rotation": [
        0,
        90,
        0
      ],
      "scale": [
        2.899112094338016,
        2.861579718525523,
        3.407250847104039
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30929888,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "a2c8ef7a-b137-411d-b5d6-4c05fe4afb68": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "a2c8ef7a-b137-411d-b5d6-4c05fe4afb68",
      "parent": "c3b137eb-4dbb-49ca-a0da-9df7ace9c551",
      "children": [],
      "position": [
        2.5,
        2.3307621231260267,
        -4.690684887643803e-16
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            1.7,
            6,
            10.8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "8819a953-1f35-4d53-8582-68bcfb49e35a": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "8819a953-1f35-4d53-8582-68bcfb49e35a",
      "parent": "c3b137eb-4dbb-49ca-a0da-9df7ace9c551",
      "children": [],
      "position": [
        -2.5,
        2.3307621675776886,
        4.809175992132244e-16
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            1.7,
            6,
            10.8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "2254638f-a297-46ef-adf4-2fa1edc33490": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick",
        "Grapple"
      ],
      "enabled": true,
      "resource_id": "2254638f-a297-46ef-adf4-2fa1edc33490",
      "parent": "c3b137eb-4dbb-49ca-a0da-9df7ace9c551",
      "children": [],
      "position": [
        5.84832378081046e-7,
        6.458505310312582,
        -1.5256568675070525e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.5,
            7,
            10.8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "f87f0b32-c57a-4be7-925c-708d013b9fe6": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "f87f0b32-c57a-4be7-925c-708d013b9fe6",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -44.40489979660233,
        8.257940417259002,
        8.949167772319006
      ],
      "rotation": [
        0,
        -43.638873609828956,
        0
      ],
      "scale": [
        4.589281387917414,
        5.397736653852276,
        4.589281387917414
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "37640945-7ca5-4bec-8650-cf6dad28115a": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "37640945-7ca5-4bec-8650-cf6dad28115a",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -14.292468070983887,
        3.5901182608007005,
        -31.65420150756836
      ],
      "rotation": [
        180,
        -77.81888498179326,
        180
      ],
      "scale": [
        3.114916040960876,
        4.525264060181286,
        3.114916040960876
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "a255bdfe-ae6b-4dcc-8b6d-83cebc59217e": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "a255bdfe-ae6b-4dcc-8b6d-83cebc59217e",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -24.340909357068355,
        18.89250499112574,
        61.16452898184204
      ],
      "rotation": [
        1.6132917342314697e-15,
        23.40553297255221,
        -1.3234582473689914e-14
      ],
      "scale": [
        2.502642172036901,
        2.502642172036901,
        2.502642172036901
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "43053649-9dc5-4ac1-b1b3-963f25e98b6f": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "43053649-9dc5-4ac1-b1b3-963f25e98b6f",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "991eb420-3b4e-4e8f-a865-192267815025"
      ],
      "position": [
        9.333588793657606,
        7.85,
        41.85267952968065
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "991eb420-3b4e-4e8f-a865-192267815025": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel",
        "Concrete"
      ],
      "enabled": true,
      "resource_id": "991eb420-3b4e-4e8f-a865-192267815025",
      "parent": "43053649-9dc5-4ac1-b1b3-963f25e98b6f",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "a7082d8b-7dd8-410b-b396-3a02f5ef22d4": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "a7082d8b-7dd8-410b-b396-3a02f5ef22d4",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "f5c8a39a-25c2-45c1-8cfa-cf182bd7c5a4"
      ],
      "position": [
        28.03854480670826,
        7.85,
        41.85267952968065
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "f5c8a39a-25c2-45c1-8cfa-cf182bd7c5a4": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel",
        "Concrete"
      ],
      "enabled": true,
      "resource_id": "f5c8a39a-25c2-45c1-8cfa-cf182bd7c5a4",
      "parent": "a7082d8b-7dd8-410b-b396-3a02f5ef22d4",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "33c42951-aa4f-49d9-a983-2e8615163b4e": {
      "name": "pillar_round_floor_red",
      "tags": [],
      "enabled": true,
      "resource_id": "33c42951-aa4f-49d9-a983-2e8615163b4e",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "a2768295-3979-4286-9dd3-2cfcc2dec8de"
      ],
      "position": [
        26.79651645477956,
        10.140807186031731,
        35.859776347153186
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.141443934523347,
        2.27762845224073,
        2.141443934523347
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30844156,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "a2768295-3979-4286-9dd3-2cfcc2dec8de": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "a2768295-3979-4286-9dd3-2cfcc2dec8de",
      "parent": "33c42951-aa4f-49d9-a983-2e8615163b4e",
      "children": [],
      "position": [
        5.662551139096195e-8,
        2.195946879445093,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "cylinder",
          "halfExtents": [
            1.51,
            1.51,
            1.51
          ],
          "radius": 1.6,
          "axis": 1,
          "height": 10.5,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "9c31ad4d-4b3d-42b0-a36f-257909b6d219": {
      "name": "pillar_round_floor_red",
      "tags": [],
      "enabled": true,
      "resource_id": "9c31ad4d-4b3d-42b0-a36f-257909b6d219",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "52faad5d-2cb6-4d38-bf95-7899849b9a45"
      ],
      "position": [
        16.11057168613979,
        10.140807186031731,
        35.859776347153186
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.141443934523347,
        2.27762845224073,
        2.141443934523347
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30844156,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "52faad5d-2cb6-4d38-bf95-7899849b9a45": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "52faad5d-2cb6-4d38-bf95-7899849b9a45",
      "parent": "9c31ad4d-4b3d-42b0-a36f-257909b6d219",
      "children": [],
      "position": [
        5.662551139096195e-8,
        2.195946879445093,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "cylinder",
          "halfExtents": [
            1.51,
            1.51,
            1.51
          ],
          "radius": 1.6,
          "axis": 1,
          "height": 10.5,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "9b30987b-838a-43a3-bcda-8b87d89a7a5a": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "9b30987b-838a-43a3-bcda-8b87d89a7a5a",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "4ffca937-333b-4768-9516-72c92f624e58"
      ],
      "position": [
        17.122918904286692,
        19.679668710054393,
        42.77278229759297
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "4ffca937-333b-4768-9516-72c92f624e58": {
      "name": "Collision",
      "tags": [
        "Invisible"
      ],
      "enabled": true,
      "resource_id": "4ffca937-333b-4768-9516-72c92f624e58",
      "parent": "9b30987b-838a-43a3-bcda-8b87d89a7a5a",
      "children": [],
      "position": [
        3.9617517106808293,
        4.009591099702163,
        3.453228600847069e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            18.703,
            7,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "1023878b-4785-4f0b-ad56-a1b18fa65802": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "1023878b-4785-4f0b-ad56-a1b18fa65802",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "9b84f442-96e9-4db3-909e-9858008176d4"
      ],
      "position": [
        36.02638065154145,
        19.679668710054393,
        42.77278229759297
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "9b84f442-96e9-4db3-909e-9858008176d4": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel",
        "Grapple"
      ],
      "enabled": true,
      "resource_id": "9b84f442-96e9-4db3-909e-9858008176d4",
      "parent": "1023878b-4785-4f0b-ad56-a1b18fa65802",
      "children": [],
      "position": [
        -3.977062549660104,
        0.4999969853471953,
        3.4455965778724753
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            18.898,
            1.18,
            17.531
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "fab77d8c-eb44-4e6b-97df-0c017fde6303": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "fab77d8c-eb44-4e6b-97df-0c017fde6303",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "95d3d248-ddf3-4198-a861-0d34146bd370"
      ],
      "position": [
        28.03854480670826,
        7.85,
        60.63927792832522
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "95d3d248-ddf3-4198-a861-0d34146bd370": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "95d3d248-ddf3-4198-a861-0d34146bd370",
      "parent": "fab77d8c-eb44-4e6b-97df-0c017fde6303",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "ae7c9690-2477-4ea0-afb6-01d450336848": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "ae7c9690-2477-4ea0-afb6-01d450336848",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "cf097543-6854-486b-a58c-4879835d99b3"
      ],
      "position": [
        9.333588793657606,
        7.85,
        60.63927792832522
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "cf097543-6854-486b-a58c-4879835d99b3": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel",
        "Concrete"
      ],
      "enabled": true,
      "resource_id": "cf097543-6854-486b-a58c-4879835d99b3",
      "parent": "ae7c9690-2477-4ea0-afb6-01d450336848",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "59b72a6a-e34e-4e97-aef1-e860940a8a95": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "59b72a6a-e34e-4e97-aef1-e860940a8a95",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        36.02638065154145,
        19.679668710054393,
        61.611739257007834
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "0c07fc58-981b-4b2a-a908-24bd7a59bf86": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "0c07fc58-981b-4b2a-a908-24bd7a59bf86",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        17.122918904286692,
        19.679668710054393,
        61.611739257007834
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "bcf7a70a-66a3-43c7-9dde-e7d0075ddb35": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "bcf7a70a-66a3-43c7-9dde-e7d0075ddb35",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "580162f0-863a-446d-a344-62ad28590fd3"
      ],
      "position": [
        11.896164552754477,
        0.41173301132758594,
        56.40020618351136
      ],
      "rotation": [
        -180,
        0,
        -180
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "580162f0-863a-446d-a344-62ad28590fd3": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "580162f0-863a-446d-a344-62ad28590fd3",
      "parent": "bcf7a70a-66a3-43c7-9dde-e7d0075ddb35",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "c6654fc0-e9ff-43de-b435-d107d8261aec": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "c6654fc0-e9ff-43de-b435-d107d8261aec",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "0e8f9b53-e792-40c3-903d-f822be0adbeb"
      ],
      "position": [
        18.933438694897163,
        0.4117330113275865,
        54.36138385619623
      ],
      "rotation": [
        -180,
        -27.774574935387243,
        -180
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "0e8f9b53-e792-40c3-903d-f822be0adbeb": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "0e8f9b53-e792-40c3-903d-f822be0adbeb",
      "parent": "c6654fc0-e9ff-43de-b435-d107d8261aec",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "8ac42b05-f78d-4167-b238-eb94da259623": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "8ac42b05-f78d-4167-b238-eb94da259623",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "30ae6236-e609-4cf4-8ace-2d5103b390c3"
      ],
      "position": [
        23.002890616478624,
        0.4117330113275869,
        49.92462634222257
      ],
      "rotation": [
        -180,
        -64.03626154265814,
        180
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "30ae6236-e609-4cf4-8ace-2d5103b390c3": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "30ae6236-e609-4cf4-8ace-2d5103b390c3",
      "parent": "8ac42b05-f78d-4167-b238-eb94da259623",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "e0f2307d-d40a-413e-9062-b7b4c838a823": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "e0f2307d-d40a-413e-9062-b7b4c838a823",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "01561859-b86c-4be5-aaae-df6c27acb478"
      ],
      "position": [
        25.545254651402836,
        0.4117330113275864,
        41.39945460253451
      ],
      "rotation": [
        -179.99999999999997,
        -81.21881977411024,
        179.99999999999997
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "01561859-b86c-4be5-aaae-df6c27acb478": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "01561859-b86c-4be5-aaae-df6c27acb478",
      "parent": "e0f2307d-d40a-413e-9062-b7b4c838a823",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "5ba3ac28-84d2-46f2-88f9-ca93ca192215": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "5ba3ac28-84d2-46f2-88f9-ca93ca192215",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "b9b8bb75-a1a1-41b8-9630-f0f4cd090f5f"
      ],
      "position": [
        34.252477083860576,
        10.088842871960539,
        34.44491172856479
      ],
      "rotation": [
        180,
        0,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "b9b8bb75-a1a1-41b8-9630-f0f4cd090f5f": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "b9b8bb75-a1a1-41b8-9630-f0f4cd090f5f",
      "parent": "5ba3ac28-84d2-46f2-88f9-ca93ca192215",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "5c25c133-3873-4169-8a4c-0dfab4266032": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "5c25c133-3873-4169-8a4c-0dfab4266032",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "e50ba340-f614-4275-a2da-d9802361292c"
      ],
      "position": [
        1.3253815294935478,
        9.688500549937245,
        -47.7308654957315
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "e50ba340-f614-4275-a2da-d9802361292c": {
      "name": "Collision2",
      "tags": [
        "Rigidbody",
        "Concrete"
      ],
      "enabled": true,
      "resource_id": "e50ba340-f614-4275-a2da-d9802361292c",
      "parent": "5c25c133-3873-4169-8a4c-0dfab4266032",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0
        }
      }
    },
    "66f855c0-d587-48a9-81fe-0a3667306163": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "66f855c0-d587-48a9-81fe-0a3667306163",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "1b4dc471-1515-43bb-90ab-06870d4f143f"
      ],
      "position": [
        -17.454796170711134,
        9.688500549937245,
        -47.7308654957315
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "1b4dc471-1515-43bb-90ab-06870d4f143f": {
      "name": "Collision2",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "1b4dc471-1515-43bb-90ab-06870d4f143f",
      "parent": "66f855c0-d587-48a9-81fe-0a3667306163",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0
        }
      }
    },
    "6ac1028e-b662-488d-8e3a-001928d1c003": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "6ac1028e-b662-488d-8e3a-001928d1c003",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "1420891d-f161-4f3f-abe0-320ad6208f48"
      ],
      "position": [
        8.90134944351029,
        2.271154158864947,
        -53.942208754235324
      ],
      "rotation": [
        1.8358790399348976e-31,
        0,
        6.490713843471307e-15
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "1420891d-f161-4f3f-abe0-320ad6208f48": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "1420891d-f161-4f3f-abe0-320ad6208f48",
      "parent": "6ac1028e-b662-488d-8e3a-001928d1c003",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "64d98245-86e7-4106-9449-0b185b690a1e": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "64d98245-86e7-4106-9449-0b185b690a1e",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "74678661-d188-4f43-ad0f-f88977e5eaf8"
      ],
      "position": [
        -0.6143102501388142,
        2.271154158864946,
        -53.942208754235324
      ],
      "rotation": [
        1.8358790399348976e-31,
        0,
        6.490713843471307e-15
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "74678661-d188-4f43-ad0f-f88977e5eaf8": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "74678661-d188-4f43-ad0f-f88977e5eaf8",
      "parent": "64d98245-86e7-4106-9449-0b185b690a1e",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "3ee4213c-3f8e-4e5e-938c-da505e4c8afc": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "3ee4213c-3f8e-4e5e-938c-da505e4c8afc",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "ee5e1b06-bd04-40d5-9e79-4a6a70f6bb55"
      ],
      "position": [
        -7.487393488923945,
        2.2711541588649458,
        -51.33981229308331
      ],
      "rotation": [
        0,
        46.330001927105954,
        6.490713843471307e-15
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "ee5e1b06-bd04-40d5-9e79-4a6a70f6bb55": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "ee5e1b06-bd04-40d5-9e79-4a6a70f6bb55",
      "parent": "3ee4213c-3f8e-4e5e-938c-da505e4c8afc",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "e5feda81-af00-467c-8901-517d1cf6017f": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "e5feda81-af00-467c-8901-517d1cf6017f",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "8f54e428-101a-46a9-835d-9c4837efae38"
      ],
      "position": [
        -10.125915330802963,
        2.2711541588649453,
        -44.38687329444839
      ],
      "rotation": [
        0,
        90,
        6.490713843471307e-15
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002
        }
      }
    },
    "8f54e428-101a-46a9-835d-9c4837efae38": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "8f54e428-101a-46a9-835d-9c4837efae38",
      "parent": "e5feda81-af00-467c-8901-517d1cf6017f",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "0cca8fae-71d6-4fa0-a180-5e97c10d905f": {
      "name": "pillar_round_floor_red",
      "tags": [],
      "enabled": true,
      "resource_id": "0cca8fae-71d6-4fa0-a180-5e97c10d905f",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "435f1263-2361-4b51-b9d9-31ca5948433f"
      ],
      "position": [
        -9.845701281561574,
        8.603715208433652,
        -37.906040739168915
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.2106873323164495,
        2.873024882627761,
        3.2106873323164495
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30844156,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "435f1263-2361-4b51-b9d9-31ca5948433f": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "435f1263-2361-4b51-b9d9-31ca5948433f",
      "parent": "0cca8fae-71d6-4fa0-a180-5e97c10d905f",
      "children": [],
      "position": [
        5.662551139096195e-8,
        2.195946879445093,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "cylinder",
          "halfExtents": [
            1.51,
            1.51,
            1.51
          ],
          "radius": 2.2,
          "axis": 1,
          "height": 15,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "62f94e3a-af47-43e1-bf07-200f195103ff": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "62f94e3a-af47-43e1-bf07-200f195103ff",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -17.454796170711134,
        21.564413722751187,
        -47.7308654957315
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "b1fbbb03-0c1c-480d-a1d5-6d83fdcdfaef": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "b1fbbb03-0c1c-480d-a1d5-6d83fdcdfaef",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "1fb54daa-0c4f-4bb2-89c8-6d37fdf60302",
        "43875bbe-e14a-4172-95e8-825828cbc72c"
      ],
      "position": [
        1.3253815294935478,
        21.564413722751187,
        -47.7308654957315
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "1fb54daa-0c4f-4bb2-89c8-6d37fdf60302": {
      "name": "Collision2",
      "tags": [
        "Rigidbody",
        "Grapple",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "1fb54daa-0c4f-4bb2-89c8-6d37fdf60302",
      "parent": "b1fbbb03-0c1c-480d-a1d5-6d83fdcdfaef",
      "children": [],
      "position": [
        -3.984285701545953,
        0.5194356603941439,
        -6.377858881023712e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            18.792,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0
        }
      }
    },
    "bb062bc1-d668-40e2-97b9-3d94cb2d1d59": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "bb062bc1-d668-40e2-97b9-3d94cb2d1d59",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -19.275063716712992,
        2.2711541588649435,
        -38.4555409066014
      ],
      "rotation": [
        1.8358790399348976e-31,
        0,
        6.490713843471307e-15
      ],
      "scale": [
        3.7070573299243033,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "e8fb97a5-a778-49ff-b7e6-435b386a0763": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "e8fb97a5-a778-49ff-b7e6-435b386a0763",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -20.6659920697979,
        0,
        -40.733832519740986
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "885da80f-d239-4ab4-a2b0-ddd32bf6dfe1": {
      "name": "pillar_round_floor_red",
      "tags": [],
      "enabled": true,
      "resource_id": "885da80f-d239-4ab4-a2b0-ddd32bf6dfe1",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "8b80a17c-23fb-4dba-b427-108963609fd8"
      ],
      "position": [
        7.977843577278676,
        11.895549221892756,
        -40.61182861221592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.141443934523347,
        2.27762845224073,
        2.141443934523347
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30844156,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "8b80a17c-23fb-4dba-b427-108963609fd8": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "8b80a17c-23fb-4dba-b427-108963609fd8",
      "parent": "885da80f-d239-4ab4-a2b0-ddd32bf6dfe1",
      "children": [],
      "position": [
        5.662551139096195e-8,
        2.195946879445093,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "cylinder",
          "halfExtents": [
            1.51,
            1.51,
            1.51
          ],
          "radius": 1.6,
          "axis": 1,
          "height": 10.5,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "4ec03234-2d9f-49e6-abce-283a788de6d8": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "4ec03234-2d9f-49e6-abce-283a788de6d8",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "8832d03d-c4ea-4889-ab6e-f0201642ca0c"
      ],
      "position": [
        8.154682159423828,
        0,
        3.652954501897838
      ],
      "rotation": [
        0,
        -5.584952414167739,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197280,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "8832d03d-c4ea-4889-ab6e-f0201642ca0c": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "8832d03d-c4ea-4889-ab6e-f0201642ca0c",
      "parent": "4ec03234-2d9f-49e6-abce-283a788de6d8",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "d229d8a2-f4d7-44dd-8c91-173531c4e88c": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "d229d8a2-f4d7-44dd-8c91-173531c4e88c",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "4d3fcbe3-779f-4b9b-80e7-12143329cf5d"
      ],
      "position": [
        8.774965831508501,
        0,
        -22.940719604492188
      ],
      "rotation": [
        0,
        -5.584952414167739,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197285,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "4d3fcbe3-779f-4b9b-80e7-12143329cf5d": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "4d3fcbe3-779f-4b9b-80e7-12143329cf5d",
      "parent": "d229d8a2-f4d7-44dd-8c91-173531c4e88c",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "98bf129c-6000-4e97-98ac-e3dd0ccd8aaa": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "98bf129c-6000-4e97-98ac-e3dd0ccd8aaa",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "13506305-eb23-443a-9c01-08b37a3810b1"
      ],
      "position": [
        4.281447237567957,
        0,
        -19.84396743774414
      ],
      "rotation": [
        0,
        26.433267625651283,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197280,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "13506305-eb23-443a-9c01-08b37a3810b1": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "13506305-eb23-443a-9c01-08b37a3810b1",
      "parent": "98bf129c-6000-4e97-98ac-e3dd0ccd8aaa",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "fd15a466-5ba8-4587-b000-2150c2bd2316": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "fd15a466-5ba8-4587-b000-2150c2bd2316",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "7b275d4b-68b4-4185-9390-a1733a5bdb63"
      ],
      "position": [
        34.55541580779987,
        0,
        1.2427420616149902
      ],
      "rotation": [
        0,
        -2.893635398054672,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197280,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "7b275d4b-68b4-4185-9390-a1733a5bdb63": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "7b275d4b-68b4-4185-9390-a1733a5bdb63",
      "parent": "fd15a466-5ba8-4587-b000-2150c2bd2316",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "3a1f54ea-f296-4341-9d0c-6cf9cf60cb3c": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "3a1f54ea-f296-4341-9d0c-6cf9cf60cb3c",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "043b886d-d97e-40d7-a015-afce1d9f39c2"
      ],
      "position": [
        30.2120011686849,
        0,
        2.2890336513519287
      ],
      "rotation": [
        0,
        -2.893635398054672,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197280,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "043b886d-d97e-40d7-a015-afce1d9f39c2": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "043b886d-d97e-40d7-a015-afce1d9f39c2",
      "parent": "3a1f54ea-f296-4341-9d0c-6cf9cf60cb3c",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "f49febf7-79e8-4818-bfec-3ac3077dc1ee": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "f49febf7-79e8-4818-bfec-3ac3077dc1ee",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "b55a51a8-591d-4ac1-83fa-f5121e066619"
      ],
      "position": [
        32.2365837097168,
        3.9863555431365967,
        1.7806466112693755
      ],
      "rotation": [
        0,
        11.342451078559282,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197285,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "b55a51a8-591d-4ac1-83fa-f5121e066619": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "b55a51a8-591d-4ac1-83fa-f5121e066619",
      "parent": "f49febf7-79e8-4818-bfec-3ac3077dc1ee",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "0ef95f94-9b54-4686-82dd-62f5e3db9120": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "0ef95f94-9b54-4686-82dd-62f5e3db9120",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "30c53f2a-c586-481c-a4be-bc519e4b8fc2"
      ],
      "position": [
        -7.925713062286377,
        0,
        10.609839474408023
      ],
      "rotation": [
        0,
        8.351440703722751,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197280,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "30c53f2a-c586-481c-a4be-bc519e4b8fc2": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "30c53f2a-c586-481c-a4be-bc519e4b8fc2",
      "parent": "0ef95f94-9b54-4686-82dd-62f5e3db9120",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "5e77c6a2-a083-4d76-b81a-a92a9ad69ab5": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "5e77c6a2-a083-4d76-b81a-a92a9ad69ab5",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "2262eb4a-3afb-44b0-ba67-b34137f0b93b"
      ],
      "position": [
        -36.10456085205078,
        0,
        -0.9203909448618603
      ],
      "rotation": [
        0,
        8.351440703722751,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197280,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "2262eb4a-3afb-44b0-ba67-b34137f0b93b": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "2262eb4a-3afb-44b0-ba67-b34137f0b93b",
      "parent": "5e77c6a2-a083-4d76-b81a-a92a9ad69ab5",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "bceb3fd9-e5f3-4534-9b9b-51cc81248eb9": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "bceb3fd9-e5f3-4534-9b9b-51cc81248eb9",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "1e18b7b1-1740-4c56-920d-082a0cb2c096"
      ],
      "position": [
        -34.3973632298832,
        0,
        -14.576383590698242
      ],
      "rotation": [
        0,
        -28.789413447115834,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018396,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "1e18b7b1-1740-4c56-920d-082a0cb2c096": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "1e18b7b1-1740-4c56-920d-082a0cb2c096",
      "parent": "bceb3fd9-e5f3-4534-9b9b-51cc81248eb9",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "550d8cd7-5271-4e26-94e4-67527d9f4bbf": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "550d8cd7-5271-4e26-94e4-67527d9f4bbf",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "85fc05cd-9329-40b3-aed6-a72274fa21fd"
      ],
      "position": [
        -8.942108954177138,
        0,
        -15.608244895935059
      ],
      "rotation": [
        0,
        -28.789413447115834,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018396,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "85fc05cd-9329-40b3-aed6-a72274fa21fd": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "85fc05cd-9329-40b3-aed6-a72274fa21fd",
      "parent": "550d8cd7-5271-4e26-94e4-67527d9f4bbf",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "ff9d2d1e-8c90-4bb9-a71e-61fa8ca0654a": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "ff9d2d1e-8c90-4bb9-a71e-61fa8ca0654a",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "d7b154ef-2fd5-45e1-bee9-0eb6804408ed"
      ],
      "position": [
        -8.942109107971191,
        0,
        -0.485089636308377
      ],
      "rotation": [
        0,
        -28.789413447115834,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 29700044,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "d7b154ef-2fd5-45e1-bee9-0eb6804408ed": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "d7b154ef-2fd5-45e1-bee9-0eb6804408ed",
      "parent": "ff9d2d1e-8c90-4bb9-a71e-61fa8ca0654a",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "72dff8af-1a51-47fc-a3a4-30db7b6ab852": {
      "name": "arch_1_shade_1",
      "tags": [],
      "enabled": true,
      "resource_id": "72dff8af-1a51-47fc-a3a4-30db7b6ab852",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "ec293fb4-9ac2-49cf-9d54-ad121c2a2364",
        "e855b809-195d-4820-8a7b-fc0a7e4ff708",
        "8a126521-aece-4a14-98bf-3e9a88c529d2"
      ],
      "position": [
        -42.10562239312584,
        -3.844043731689453,
        -8.253822326660156
      ],
      "rotation": [
        180,
        90,
        180
      ],
      "scale": [
        7.525091683243699,
        7.686463391639226,
        6.185641263332534
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018389,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "ec293fb4-9ac2-49cf-9d54-ad121c2a2364": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "ec293fb4-9ac2-49cf-9d54-ad121c2a2364",
      "parent": "72dff8af-1a51-47fc-a3a4-30db7b6ab852",
      "children": [],
      "position": [
        0.9970445319995362,
        1.6763371501775282,
        -0.006462602746068136
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2.8,
            11,
            2.22
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "e855b809-195d-4820-8a7b-fc0a7e4ff708": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "e855b809-195d-4820-8a7b-fc0a7e4ff708",
      "parent": "72dff8af-1a51-47fc-a3a4-30db7b6ab852",
      "children": [],
      "position": [
        -0.9998505457887049,
        1.8880913358058484,
        -0.006462602746069024
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2.8,
            11,
            2.22
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "82d0e653-18da-4155-a1a9-7e1e3833768e": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "82d0e653-18da-4155-a1a9-7e1e3833768e",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "9e54c183-5cc3-4869-8578-65dd80fde50d"
      ],
      "position": [
        -44.74555169291986,
        0,
        3.7129390239715576
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "9e54c183-5cc3-4869-8578-65dd80fde50d": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "9e54c183-5cc3-4869-8578-65dd80fde50d",
      "parent": "82d0e653-18da-4155-a1a9-7e1e3833768e",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "55b57729-acfa-4e78-bd5b-ed4dc7033bde": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "55b57729-acfa-4e78-bd5b-ed4dc7033bde",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "e2bf1e91-9127-4f3c-adc3-d60c090abd0e"
      ],
      "position": [
        -50.3462028503418,
        0,
        7.694899642072976
      ],
      "rotation": [
        0,
        90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "e2bf1e91-9127-4f3c-adc3-d60c090abd0e": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "e2bf1e91-9127-4f3c-adc3-d60c090abd0e",
      "parent": "55b57729-acfa-4e78-bd5b-ed4dc7033bde",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "1f74d11d-9bc1-43f1-9a8f-0334dbd45572": {
      "name": "Bounce",
      "tags": [
        "BouncePad"
      ],
      "enabled": true,
      "resource_id": "1f74d11d-9bc1-43f1-9a8f-0334dbd45572",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -61.87532321903037,
        0.39114561676979065,
        8.117319107055664
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.9,
        2.817224769653252,
        2.9
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 29932663,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        },
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2.9,
            0.45,
            2.9
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "176cf9b8-ddf6-46ef-b6dc-3af008d34367": {
      "name": "Balcony",
      "tags": [],
      "enabled": true,
      "resource_id": "176cf9b8-ddf6-46ef-b6dc-3af008d34367",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "a6b57d5a-1f5c-4bff-865c-ca688bee3088",
        "e1a7d145-87c5-4af9-8000-91236b009fca",
        "3177ce5e-32f6-4d9e-bdef-b9a56b80d048",
        "9ea8edcf-13e9-4e1e-978d-1c0243524e6d",
        "a0e12a44-4896-4f53-b912-ee7747d047e5",
        "233162ac-3c42-4358-900e-67721eba3ddf",
        "d287fc94-a957-4b38-a884-a9b9156a885f",
        "62124c1d-223c-4d9b-b2a8-8fea7ccabca2",
        "541437fe-e87b-4e4b-b5bd-2b120c9f2f5b",
        "8495f353-d6f2-4b63-bd87-991908ad65f3",
        "9b73994b-88d8-4dc0-b698-0ed577bf0a1f",
        "e5556b97-2ac5-441a-a483-0f35a75288f0",
        "a6c91bf8-ca37-4d1d-a08c-9b093e3717f0",
        "5ad2affc-8a6c-40d6-a59d-39dd726664bf",
        "196ad0e8-260e-43cd-af2d-341831820c9a",
        "5729286f-f54d-477e-b03c-3c6a44d8dc5e",
        "22e89aa3-90ac-4029-baa8-0b841d039fa4",
        "5c85c78a-fc22-41a3-9b69-9229c24d954d",
        "df0f89e3-11b7-43ca-8a2c-d544e028e819",
        "1c072d8c-6383-45ca-83f6-8842b9dd6dd2",
        "0fcb6d71-1066-452a-bc49-421edcfd5925",
        "23b8612f-7051-461e-aa00-79d26fb90e29",
        "a2a4b7b8-657d-482c-9bb7-74781ac6b163",
        "5a942138-e9ba-402b-a241-e873bb4945f7",
        "ab887808-c837-40d1-b6fc-2b53554a2eaf",
        "c9a0b842-3a64-4970-bd60-6e92abfc0333",
        "9805a7d4-838f-4887-b1b6-809f59d904ef",
        "6dca7e7d-65ba-4f5c-8a81-6323f517578d",
        "e4579fbe-05bb-4755-95cc-840ac850ad2e",
        "fa37361c-854c-49b8-ac7b-0567199cf43e",
        "392067cc-b07a-4041-9458-91943dbf7361",
        "a1be1753-8330-4b74-95ef-9699d1ba85f6"
      ],
      "position": [
        0,
        0,
        0
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "930cbf46-cd9f-4289-9f1e-6c498ee13094": {
      "name": "Balcony",
      "tags": [],
      "enabled": true,
      "resource_id": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "6f7f967a-559e-45f0-b2f8-36f23a6fbc8a",
        "2d1a0cdf-8ccc-42cb-9f77-819f8dcbd01d",
        "58ec9d05-7caf-4144-9bbf-b1067985d793",
        "92cfd675-6259-4262-b96b-3f7add59db06",
        "2058429b-704f-4419-94cf-3a931416487a",
        "aa9fc876-35e0-46e1-b164-09325f33f550",
        "252418c2-ded6-451e-bd52-23c6260524f4",
        "fc3e198c-b2ce-46e5-a626-0dd982a8b828",
        "c1b3ddb3-f0df-41f9-b94f-ce98ca0e2c4d",
        "1225e5d4-d138-4218-8053-dfa898af0d65",
        "d32dfdb5-5153-495e-8294-db88ed5c0a23",
        "e84fdf83-700a-4ae9-94b7-b29a07a3759a",
        "e135e374-b9d7-49b8-9862-7a7134c5f2ab",
        "668707e5-6acf-44bb-8201-c507e8ad9871",
        "5fba813e-1abb-478c-bbb9-d2ccbbe31df2",
        "feb94e27-cb99-4640-816b-a90da4af903c",
        "ca479397-3b6b-4d32-b06b-e5222d2a5863",
        "c41eb9eb-e4ce-458c-b380-11298be8158b",
        "6023b35a-b374-4d2e-bf71-df01843ffa24",
        "f7c0a80c-386a-4b4e-acd6-b4cbfce3ac1a",
        "ffb0a1c9-337f-4a17-bad7-a5d5421da760",
        "7bc79f3e-52a2-44c0-b7a8-44b3f9a67905",
        "436c5d84-fb20-4580-a3ab-f3e51e76bbf1",
        "d44cf2ba-a425-439d-80c7-b49c17364caa",
        "ff6e3af7-c8a8-4767-95b4-cb47ff6dc490",
        "d36bfe5d-3784-41d1-aa00-988ccf7b82f6",
        "5e994e69-df47-4d5f-8c00-af362ee6c580",
        "c2591da9-4e7e-49e1-8a6a-a715604b02d5",
        "d37df7f0-c802-4c7f-a50b-15d60c819a8e",
        "3685f3ad-2e2c-499d-ad5c-8c35991018ae",
        "93bf0b3a-0e48-4b51-85c4-f7ffdaf3720b"
      ],
      "position": [
        -0.7595662241501717,
        6.401312613378663e-16,
        15.079771995544434
      ],
      "rotation": [
        -180,
        0,
        -180
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "6f7f967a-559e-45f0-b2f8-36f23a6fbc8a": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "6f7f967a-559e-45f0-b2f8-36f23a6fbc8a",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "27b3fd92-db47-4d8f-970e-fa66b5c7664b"
      ],
      "position": [
        49.49173837900162,
        -3.548812759646111e-15,
        -0.5113137958754308
      ],
      "rotation": [
        -2.5444437451708134e-14,
        3.449914803592871e-45,
        1.5537035023920813e-29
      ],
      "scale": [
        3.982600780221009,
        3.0840293312107256,
        2.9049360745341204
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "27b3fd92-db47-4d8f-970e-fa66b5c7664b": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "27b3fd92-db47-4d8f-970e-fa66b5c7664b",
      "parent": "6f7f967a-559e-45f0-b2f8-36f23a6fbc8a",
      "children": [],
      "position": [
        -0.0000034340746424277313,
        1.7617526934961976,
        7.985923730635669e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            7.98,
            7,
            2.95
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "2d1a0cdf-8ccc-42cb-9f77-819f8dcbd01d": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "2d1a0cdf-8ccc-42cb-9f77-819f8dcbd01d",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "81ba6bfc-8eb7-42fc-bdc3-4171acb8a2cb"
      ],
      "position": [
        65.1458597779274,
        -3.5488135205874493e-15,
        -0.5113137958754308
      ],
      "rotation": [
        -2.5444437451708134e-14,
        3.449914803592871e-45,
        1.5537035023920813e-29
      ],
      "scale": [
        3.982600780221009,
        3.0840293312107256,
        2.9049360745341204
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "81ba6bfc-8eb7-42fc-bdc3-4171acb8a2cb": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "81ba6bfc-8eb7-42fc-bdc3-4171acb8a2cb",
      "parent": "2d1a0cdf-8ccc-42cb-9f77-819f8dcbd01d",
      "children": [],
      "position": [
        -0.0000034340746424277313,
        1.7617526934961976,
        7.985923730635669e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            7.98,
            7,
            2.95
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "58ec9d05-7caf-4144-9bbf-b1067985d793": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "58ec9d05-7caf-4144-9bbf-b1067985d793",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "99ea4369-b181-4324-b50f-7c303a1328d1"
      ],
      "position": [
        75.27461344003677,
        -4.626467314120445e-15,
        3.230281053840338
      ],
      "rotation": [
        -2.5444437451708134e-14,
        -90,
        0
      ],
      "scale": [
        3.982600780221009,
        3.0840293312107256,
        2.9049360745341204
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "99ea4369-b181-4324-b50f-7c303a1328d1": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "99ea4369-b181-4324-b50f-7c303a1328d1",
      "parent": "58ec9d05-7caf-4144-9bbf-b1067985d793",
      "children": [],
      "position": [
        0.5608397002795344,
        4.209883588640485,
        4.103643647113131e-9
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            5.613,
            15,
            2.95
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "92cfd675-6259-4262-b96b-3f7add59db06": {
      "name": "pillar_round_floor_red",
      "tags": [],
      "enabled": true,
      "resource_id": "92cfd675-6259-4262-b96b-3f7add59db06",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "0d6d86f8-06be-42f6-8ab7-2b8b60860de7"
      ],
      "position": [
        44.61039733886719,
        14.225613594055176,
        -8.353169535502232
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.141443934523347,
        2.27762845224073,
        2.141443934523347
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30844156,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "0d6d86f8-06be-42f6-8ab7-2b8b60860de7": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "0d6d86f8-06be-42f6-8ab7-2b8b60860de7",
      "parent": "92cfd675-6259-4262-b96b-3f7add59db06",
      "children": [],
      "position": [
        5.662551139096195e-8,
        2.195946879445093,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "cylinder",
          "halfExtents": [
            1.51,
            1.51,
            1.51
          ],
          "radius": 1.6,
          "axis": 1,
          "height": 10.5,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "aa9fc876-35e0-46e1-b164-09325f33f550": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "aa9fc876-35e0-46e1-b164-09325f33f550",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "b5d84734-b0c0-4cac-9e11-9ddb66df5598"
      ],
      "position": [
        51.58736038208008,
        11.90999984741211,
        -7.161457538604736
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "b5d84734-b0c0-4cac-9e11-9ddb66df5598": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel",
        "Concrete"
      ],
      "enabled": true,
      "resource_id": "b5d84734-b0c0-4cac-9e11-9ddb66df5598",
      "parent": "aa9fc876-35e0-46e1-b164-09325f33f550",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "252418c2-ded6-451e-bd52-23c6260524f4": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "252418c2-ded6-451e-bd52-23c6260524f4",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "77a4c2dd-8136-49f2-9eb8-0da38eebc89a"
      ],
      "position": [
        51.16624750606519,
        23.969753265380863,
        -7.237765312194828
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.523340323898247,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "77a4c2dd-8136-49f2-9eb8-0da38eebc89a": {
      "name": "Collision",
      "tags": [
        "Invisible"
      ],
      "enabled": true,
      "resource_id": "77a4c2dd-8136-49f2-9eb8-0da38eebc89a",
      "parent": "252418c2-ded6-451e-bd52-23c6260524f4",
      "children": [],
      "position": [
        3.489019286188241,
        3.0286834773538986,
        -3.071922568669836
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            18.881,
            5,
            16.564
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "fc3e198c-b2ce-46e5-a626-0dd982a8b828": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "fc3e198c-b2ce-46e5-a626-0dd982a8b828",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "b5cb549c-45b0-4f78-8357-6466731d50eb"
      ],
      "position": [
        70.35665893554688,
        23.96975326538086,
        -7.237765312194824
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "b5cb549c-45b0-4f78-8357-6466731d50eb": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel",
        "Grapple"
      ],
      "enabled": true,
      "resource_id": "b5cb549c-45b0-4f78-8357-6466731d50eb",
      "parent": "fc3e198c-b2ce-46e5-a626-0dd982a8b828",
      "children": [],
      "position": [
        -2.0182369553367607e-7,
        2.538392008212929,
        9.973036849686423e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            6,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "c1b3ddb3-f0df-41f9-b94f-ce98ca0e2c4d": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "c1b3ddb3-f0df-41f9-b94f-ce98ca0e2c4d",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "0701b166-4111-4a6b-a635-455cc4713e8f"
      ],
      "position": [
        50.49409967660904,
        23.969753265380863,
        -19.53696799854788
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "0701b166-4111-4a6b-a635-455cc4713e8f": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel",
        "Grapple"
      ],
      "enabled": true,
      "resource_id": "0701b166-4111-4a6b-a635-455cc4713e8f",
      "parent": "c1b3ddb3-f0df-41f9-b94f-ce98ca0e2c4d",
      "children": [],
      "position": [
        4.284405225128862,
        0.5,
        2.734488577302826
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            19.562,
            1.18,
            15.32
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "1225e5d4-d138-4218-8053-dfa898af0d65": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "1225e5d4-d138-4218-8053-dfa898af0d65",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "eaff37c7-d7d4-4c94-97ec-e276c97b5c2d"
      ],
      "position": [
        70.4404296875,
        11.90999984741211,
        -7.161457538604736
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "eaff37c7-d7d4-4c94-97ec-e276c97b5c2d": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel",
        "Concrete"
      ],
      "enabled": true,
      "resource_id": "eaff37c7-d7d4-4c94-97ec-e276c97b5c2d",
      "parent": "1225e5d4-d138-4218-8053-dfa898af0d65",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "d32dfdb5-5153-495e-8294-db88ed5c0a23": {
      "name": "ground_block_8x1x8",
      "tags": [],
      "enabled": true,
      "resource_id": "d32dfdb5-5153-495e-8294-db88ed5c0a23",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "dc8d2d60-281a-47b2-97af-1c8cfdeebbec"
      ],
      "position": [
        51.58736038208008,
        11.90999984741211,
        -26.046262741088867
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.36001631710047,
        2.36001631710047,
        2.36001631710047
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30537578,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "dc8d2d60-281a-47b2-97af-1c8cfdeebbec": {
      "name": "Collision2",
      "tags": [
        "Rigidbody",
        "Concrete"
      ],
      "enabled": true,
      "resource_id": "dc8d2d60-281a-47b2-97af-1c8cfdeebbec",
      "parent": "d32dfdb5-5153-495e-8294-db88ed5c0a23",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            9.5,
            1.18,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0
        }
      }
    },
    "e84fdf83-700a-4ae9-94b7-b29a07a3759a": {
      "name": "ramp_straight_shade_4",
      "tags": [],
      "enabled": true,
      "resource_id": "e84fdf83-700a-4ae9-94b7-b29a07a3759a",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "359ac1b1-117b-436f-ba97-467a207839b9"
      ],
      "position": [
        39.8317985534668,
        9.615044593811035,
        -0.934255902794014
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        4.7374174024643665,
        4.7374174024643665,
        4.7374174024643665
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30028242,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100003
        }
      }
    },
    "e135e374-b9d7-49b8-9862-7a7134c5f2ab": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "e135e374-b9d7-49b8-9862-7a7134c5f2ab",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "c32f3709-14e7-4403-b8c0-b516ecc3c780"
      ],
      "position": [
        46.832481384277344,
        4.609103679656982,
        -0.7046934962272644
      ],
      "rotation": [
        -180,
        -1.539493938844084e-38,
        -180
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002,
          "mapping": {
            "0": 30715520
          }
        }
      }
    },
    "c32f3709-14e7-4403-b8c0-b516ecc3c780": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "c32f3709-14e7-4403-b8c0-b516ecc3c780",
      "parent": "e135e374-b9d7-49b8-9862-7a7134c5f2ab",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "668707e5-6acf-44bb-8201-c507e8ad9871": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "668707e5-6acf-44bb-8201-c507e8ad9871",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "a025fa8c-c011-41f3-8797-46087022d8fa"
      ],
      "position": [
        74.47208404541016,
        4.609103679656982,
        -0.7046934962272644
      ],
      "rotation": [
        -180,
        -1.539493938844084e-38,
        -180
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002,
          "mapping": {
            "0": 30715520
          }
        }
      }
    },
    "a025fa8c-c011-41f3-8797-46087022d8fa": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "a025fa8c-c011-41f3-8797-46087022d8fa",
      "parent": "668707e5-6acf-44bb-8201-c507e8ad9871",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "5fba813e-1abb-478c-bbb9-d2ccbbe31df2": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "5fba813e-1abb-478c-bbb9-d2ccbbe31df2",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "ba461014-5513-4b48-ae4a-28b331b158b9"
      ],
      "position": [
        76.89762878417969,
        4.609103679656982,
        -5.493612766265869
      ],
      "rotation": [
        6.490714038905489e-15,
        -90,
        0
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002,
          "mapping": {
            "0": 30715520
          }
        }
      }
    },
    "ba461014-5513-4b48-ae4a-28b331b158b9": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "ba461014-5513-4b48-ae4a-28b331b158b9",
      "parent": "5fba813e-1abb-478c-bbb9-d2ccbbe31df2",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "feb94e27-cb99-4640-816b-a90da4af903c": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "feb94e27-cb99-4640-816b-a90da4af903c",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "050eff0f-c1e6-45a7-9596-9ff42fbe1572"
      ],
      "position": [
        76.89762878417969,
        4.609103679656982,
        -15.030766487121582
      ],
      "rotation": [
        6.490714038905489e-15,
        -90,
        0
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002,
          "mapping": {
            "0": 30715520
          }
        }
      }
    },
    "050eff0f-c1e6-45a7-9596-9ff42fbe1572": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "050eff0f-c1e6-45a7-9596-9ff42fbe1572",
      "parent": "feb94e27-cb99-4640-816b-a90da4af903c",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "ca479397-3b6b-4d32-b06b-e5222d2a5863": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "ca479397-3b6b-4d32-b06b-e5222d2a5863",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "fe3a45e9-f251-43f8-ae29-698985430a0f"
      ],
      "position": [
        74.16320037841797,
        4.609103679656982,
        -15.030766487121582
      ],
      "rotation": [
        -7.176245110003047e-30,
        4.0647806241547295e-46,
        6.490714038905497e-15
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002,
          "mapping": {
            "0": 30715520
          }
        }
      }
    },
    "fe3a45e9-f251-43f8-ae29-698985430a0f": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "fe3a45e9-f251-43f8-ae29-698985430a0f",
      "parent": "ca479397-3b6b-4d32-b06b-e5222d2a5863",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "c41eb9eb-e4ce-458c-b380-11298be8158b": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "c41eb9eb-e4ce-458c-b380-11298be8158b",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "1dbf9910-d4e7-494b-8274-662e8d194e24"
      ],
      "position": [
        65.02243041992188,
        4.609103679656982,
        -15.030766487121582
      ],
      "rotation": [
        -7.176245110003047e-30,
        4.0647806241547295e-46,
        6.490714038905497e-15
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002,
          "mapping": {
            "0": 30715520
          }
        }
      }
    },
    "1dbf9910-d4e7-494b-8274-662e8d194e24": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "1dbf9910-d4e7-494b-8274-662e8d194e24",
      "parent": "c41eb9eb-e4ce-458c-b380-11298be8158b",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "6023b35a-b374-4d2e-bf71-df01843ffa24": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "6023b35a-b374-4d2e-bf71-df01843ffa24",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "b6caafbc-f173-45c0-81ce-1a7c34fb55a7"
      ],
      "position": [
        59.722382605075836,
        4.609103679656986,
        -19.444411737609528
      ],
      "rotation": [
        6.490714038905496e-15,
        -90,
        0
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002,
          "mapping": {
            "0": 30715520
          }
        }
      }
    },
    "b6caafbc-f173-45c0-81ce-1a7c34fb55a7": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "b6caafbc-f173-45c0-81ce-1a7c34fb55a7",
      "parent": "6023b35a-b374-4d2e-bf71-df01843ffa24",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "f7c0a80c-386a-4b4e-acd6-b4cbfce3ac1a": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "f7c0a80c-386a-4b4e-acd6-b4cbfce3ac1a",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "55fa8eaf-6349-4860-8f15-5f79accc7640"
      ],
      "position": [
        57.260956823825836,
        4.609103679656986,
        -22.171930376154904
      ],
      "rotation": [
        3.94347681867677e-23,
        -54.23608302574899,
        6.4907138120683975e-15
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002,
          "mapping": {
            "0": 30715520
          }
        }
      }
    },
    "55fa8eaf-6349-4860-8f15-5f79accc7640": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "55fa8eaf-6349-4860-8f15-5f79accc7640",
      "parent": "f7c0a80c-386a-4b4e-acd6-b4cbfce3ac1a",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "ffb0a1c9-337f-4a17-bad7-a5d5421da760": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "ffb0a1c9-337f-4a17-bad7-a5d5421da760",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "b756530a-f745-4298-99ea-8738210b91c9"
      ],
      "position": [
        50.38163477182388,
        4.609103679656984,
        -25.81569868670178
      ],
      "rotation": [
        1.835878950436921e-31,
        -1.039881591506334e-47,
        6.490714038905497e-15
      ],
      "scale": [
        2.4262256217590603,
        2.4262256217590603,
        2.4262256217590603
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30535975,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100002,
          "mapping": {
            "0": 30715520
          }
        }
      }
    },
    "b756530a-f745-4298-99ea-8738210b91c9": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Rock"
      ],
      "enabled": true,
      "resource_id": "b756530a-f745-4298-99ea-8738210b91c9",
      "parent": "ffb0a1c9-337f-4a17-bad7-a5d5421da760",
      "children": [],
      "position": [
        9.753232461662265e-7,
        5.985993180229796,
        -0.4899808716413548
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4.9,
            5,
            1.25
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "b518b1fa-6474-4008-84f9-2aeaaddd7180": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "b518b1fa-6474-4008-84f9-2aeaaddd7180",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "026efe24-bc33-4e10-95a5-731e55e6990b"
      ],
      "position": [
        -49.87635040283203,
        -3.118680867616715e-15,
        -18.9169921875
      ],
      "rotation": [
        -1.4033418697203106e-14,
        3.975344045709257e-30,
        3.947785528429057e-14
      ],
      "scale": [
        3.982600780221009,
        3.0840293312107256,
        2.9049360745341204
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "026efe24-bc33-4e10-95a5-731e55e6990b": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "026efe24-bc33-4e10-95a5-731e55e6990b",
      "parent": "b518b1fa-6474-4008-84f9-2aeaaddd7180",
      "children": [],
      "position": [
        -8.573879295425968e-7,
        1.7634803247488717,
        8.467241636722633e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            7.98,
            7,
            2.95
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "5a1e75cd-4b0a-4230-a729-b2064a4c8dca": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "5a1e75cd-4b0a-4230-a729-b2064a4c8dca",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "85407ca4-cfd4-45a4-a309-d8f541a35df7"
      ],
      "position": [
        -60.28953552246094,
        -1.0315288357374327e-14,
        -19.005706787109375
      ],
      "rotation": [
        -1.4033418697203106e-14,
        3.975344045709257e-30,
        3.947785528429057e-14
      ],
      "scale": [
        3.982600780221009,
        3.0840293312107256,
        2.9049360745341204
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "85407ca4-cfd4-45a4-a309-d8f541a35df7": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "85407ca4-cfd4-45a4-a309-d8f541a35df7",
      "parent": "5a1e75cd-4b0a-4230-a729-b2064a4c8dca",
      "children": [],
      "position": [
        -0.0000034408876672387123,
        1.4344811561125372,
        6.224691446732322e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            7.98,
            8,
            2.95
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "2058429b-704f-4419-94cf-3a931416487a": {
      "name": "pillar_round_floor_red",
      "tags": [],
      "enabled": true,
      "resource_id": "2058429b-704f-4419-94cf-3a931416487a",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [
        "02cba6bb-6b4a-487c-bf30-0c989aee6c06"
      ],
      "position": [
        43.893069901429506,
        14.225613594055178,
        -26.561734199523926
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.141443934523347,
        2.27762845224073,
        2.141443934523347
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30844156,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "02cba6bb-6b4a-487c-bf30-0c989aee6c06": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "02cba6bb-6b4a-487c-bf30-0c989aee6c06",
      "parent": "2058429b-704f-4419-94cf-3a931416487a",
      "children": [],
      "position": [
        5.662551139096195e-8,
        2.195946879445093,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "cylinder",
          "halfExtents": [
            1.51,
            1.51,
            1.51
          ],
          "radius": 1.6,
          "axis": 1,
          "height": 10.5,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "7bc79f3e-52a2-44c0-b7a8-44b3f9a67905": {
      "name": "wall_pannel_01_shade_3",
      "tags": [],
      "enabled": true,
      "resource_id": "7bc79f3e-52a2-44c0-b7a8-44b3f9a67905",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [],
      "position": [
        46.42120462656021,
        26.30586624145508,
        -25.71940715633631
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        6.581725378563207,
        7.244566294022107,
        10.775200642972559
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30017386,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100004
        }
      }
    },
    "436c5d84-fb20-4580-a3ab-f3e51e76bbf1": {
      "name": "wall_pannel_01_shade_3",
      "tags": [],
      "enabled": true,
      "resource_id": "436c5d84-fb20-4580-a3ab-f3e51e76bbf1",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [],
      "position": [
        46.42120462656021,
        26.30586624145508,
        -19.252899488599603
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        6.581725378563207,
        7.244566294022107,
        10.775200642972559
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30017386,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100004
        }
      }
    },
    "d44cf2ba-a425-439d-80c7-b49c17364caa": {
      "name": "wall_pannel_01_shade_3",
      "tags": [],
      "enabled": true,
      "resource_id": "d44cf2ba-a425-439d-80c7-b49c17364caa",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [],
      "position": [
        46.42120462656021,
        26.30586624145508,
        -12.808115896330047
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        6.581725378563207,
        7.244566294022107,
        10.775200642972559
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30017386,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100004
        }
      }
    },
    "ff6e3af7-c8a8-4767-95b4-cb47ff6dc490": {
      "name": "wall_pannel_01_shade_3",
      "tags": [],
      "enabled": true,
      "resource_id": "ff6e3af7-c8a8-4767-95b4-cb47ff6dc490",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [],
      "position": [
        46.42120462656021,
        26.30586624145508,
        -6.32032003996051
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        6.581725378563207,
        7.244566294022107,
        10.775200642972559
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30017386,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100004
        }
      }
    },
    "d36bfe5d-3784-41d1-aa00-988ccf7b82f6": {
      "name": "wall_pannel_01_shade_3",
      "tags": [],
      "enabled": true,
      "resource_id": "d36bfe5d-3784-41d1-aa00-988ccf7b82f6",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [],
      "position": [
        46.42120462656021,
        26.30586624145508,
        -1.1456394675310513
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        6.581725378563207,
        7.244566294022107,
        10.775200642972559
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30017386,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100004
        }
      }
    },
    "5e994e69-df47-4d5f-8c00-af362ee6c580": {
      "name": "wall_pannel_01_shade_3",
      "tags": [],
      "enabled": true,
      "resource_id": "5e994e69-df47-4d5f-8c00-af362ee6c580",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [],
      "position": [
        49.27135246659013,
        26.30586624145508,
        -3.2210836410522496
      ],
      "rotation": [
        -1.186658639724803e-14,
        0,
        2.1668329391367046e-15
      ],
      "scale": [
        6.581725378563207,
        7.244566294022107,
        10.775200642972559
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30017386,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100004
        }
      }
    },
    "c2591da9-4e7e-49e1-8a6a-a715604b02d5": {
      "name": "wall_pannel_01_shade_3",
      "tags": [],
      "enabled": true,
      "resource_id": "c2591da9-4e7e-49e1-8a6a-a715604b02d5",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [],
      "position": [
        55.52908207666169,
        26.30586624145508,
        -3.2210836410522496
      ],
      "rotation": [
        -1.186658639724803e-14,
        0,
        2.1668329391367046e-15
      ],
      "scale": [
        6.581725378563207,
        7.244566294022107,
        10.775200642972559
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30017386,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100004
        }
      }
    },
    "d37df7f0-c802-4c7f-a50b-15d60c819a8e": {
      "name": "wall_pannel_01_shade_3",
      "tags": [],
      "enabled": true,
      "resource_id": "d37df7f0-c802-4c7f-a50b-15d60c819a8e",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [],
      "position": [
        61.714004766872996,
        26.30586624145508,
        -3.2210836410522496
      ],
      "rotation": [
        -1.186658639724803e-14,
        0,
        2.1668329391367046e-15
      ],
      "scale": [
        6.581725378563207,
        7.244566294022107,
        10.775200642972559
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30017386,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100004
        }
      }
    },
    "3685f3ad-2e2c-499d-ad5c-8c35991018ae": {
      "name": "wall_pannel_01_shade_3",
      "tags": [],
      "enabled": true,
      "resource_id": "3685f3ad-2e2c-499d-ad5c-8c35991018ae",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [],
      "position": [
        68.07473707124925,
        26.30586624145508,
        -3.2210836410522496
      ],
      "rotation": [
        -1.186658639724803e-14,
        0,
        2.1668329391367046e-15
      ],
      "scale": [
        6.581725378563207,
        7.244566294022107,
        10.775200642972559
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30017386,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100004
        }
      }
    },
    "93bf0b3a-0e48-4b51-85c4-f7ffdaf3720b": {
      "name": "wall_pannel_01_shade_3",
      "tags": [],
      "enabled": true,
      "resource_id": "93bf0b3a-0e48-4b51-85c4-f7ffdaf3720b",
      "parent": "930cbf46-cd9f-4289-9f1e-6c498ee13094",
      "children": [],
      "position": [
        75.37314248961717,
        26.305866241455085,
        -3.2210836410522496
      ],
      "rotation": [
        -1.186658639724803e-14,
        0,
        2.1668329391367046e-15
      ],
      "scale": [
        8.962913747526205,
        7.244566294022107,
        10.775200642972559
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30017386,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100004
        }
      }
    },
    "99a70f70-71c2-499b-9a7e-b6b0c7ed89e5": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "99a70f70-71c2-499b-9a7e-b6b0c7ed89e5",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "6012dd54-a964-4c0a-b9f6-7c5e279eba69"
      ],
      "position": [
        -75.38847932754358,
        14.284503936767578,
        27.051401138305664
      ],
      "rotation": [
        0,
        -42.974161702400274,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018396,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "6012dd54-a964-4c0a-b9f6-7c5e279eba69": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic"
      ],
      "enabled": true,
      "resource_id": "6012dd54-a964-4c0a-b9f6-7c5e279eba69",
      "parent": "99a70f70-71c2-499b-9a7e-b6b0c7ed89e5",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "b67dcb91-1d14-4325-a5d7-6f6db8ebd878": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "b67dcb91-1d14-4325-a5d7-6f6db8ebd878",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "34099c5b-aa4d-452e-9274-306c3dede200"
      ],
      "position": [
        -60.66431141813376,
        14.284503936767578,
        27.051401138305664
      ],
      "rotation": [
        0,
        -42.974161702400274,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018396,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "34099c5b-aa4d-452e-9274-306c3dede200": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic"
      ],
      "enabled": true,
      "resource_id": "34099c5b-aa4d-452e-9274-306c3dede200",
      "parent": "b67dcb91-1d14-4325-a5d7-6f6db8ebd878",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "06e8aa66-5b83-4a92-bcce-54e7ab97f020": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "06e8aa66-5b83-4a92-bcce-54e7ab97f020",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "9d6c5b63-8de5-4b08-a576-ee9438b4e772"
      ],
      "position": [
        -57.60977073926314,
        14.284503936767578,
        33.63026809692383
      ],
      "rotation": [
        0,
        -42.974161702400274,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018396,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "9d6c5b63-8de5-4b08-a576-ee9438b4e772": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic"
      ],
      "enabled": true,
      "resource_id": "9d6c5b63-8de5-4b08-a576-ee9438b4e772",
      "parent": "06e8aa66-5b83-4a92-bcce-54e7ab97f020",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "78587634-4606-4b8c-870d-e8b4ac92fdc5": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "78587634-4606-4b8c-870d-e8b4ac92fdc5",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "6fba639b-f90c-46aa-905f-92cb836fa1a7"
      ],
      "position": [
        -47.162235260009766,
        14.284503936767578,
        38.60730121126993
      ],
      "rotation": [
        0,
        -42.974161702400274,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018396,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "6fba639b-f90c-46aa-905f-92cb836fa1a7": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic"
      ],
      "enabled": true,
      "resource_id": "6fba639b-f90c-46aa-905f-92cb836fa1a7",
      "parent": "78587634-4606-4b8c-870d-e8b4ac92fdc5",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "6ee45802-111a-451c-9477-edd9d6ba88e0": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "6ee45802-111a-451c-9477-edd9d6ba88e0",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "18bc27c2-50f2-411f-b48a-0ac092c86ce3"
      ],
      "position": [
        -7.870357301897333,
        12.042329788208008,
        -42.432823181152344
      ],
      "rotation": [
        0,
        -42.974161702400274,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018396,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "18bc27c2-50f2-411f-b48a-0ac092c86ce3": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic"
      ],
      "enabled": true,
      "resource_id": "18bc27c2-50f2-411f-b48a-0ac092c86ce3",
      "parent": "6ee45802-111a-451c-9477-edd9d6ba88e0",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "71530786-3b15-430e-9be0-144a52150634": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "71530786-3b15-430e-9be0-144a52150634",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "61d90ca4-14de-4858-a0fa-fe54ba4f2289"
      ],
      "position": [
        -3.2700679835186652,
        12.042329788208008,
        -51.750694274902344
      ],
      "rotation": [
        0,
        -42.974161702400274,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018396,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "61d90ca4-14de-4858-a0fa-fe54ba4f2289": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic"
      ],
      "enabled": true,
      "resource_id": "61d90ca4-14de-4858-a0fa-fe54ba4f2289",
      "parent": "71530786-3b15-430e-9be0-144a52150634",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "66c7a5c0-86d9-46e7-aa59-1c08c436cf27": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "66c7a5c0-86d9-46e7-aa59-1c08c436cf27",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "0dd74930-015b-416d-a25b-e1148c45e3e4"
      ],
      "position": [
        4.586314721736315,
        12.042329788208008,
        -51.750694274902344
      ],
      "rotation": [
        0,
        -42.974161702400274,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018396,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "0dd74930-015b-416d-a25b-e1148c45e3e4": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic"
      ],
      "enabled": true,
      "resource_id": "0dd74930-015b-416d-a25b-e1148c45e3e4",
      "parent": "66c7a5c0-86d9-46e7-aa59-1c08c436cf27",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "193956ac-0995-4e88-9680-77839ef61bcd": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "193956ac-0995-4e88-9680-77839ef61bcd",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        77.84832763671875,
        8.257940292358398,
        12.148984620997442
      ],
      "rotation": [
        0,
        83.07418361963212,
        0
      ],
      "scale": [
        3.823803321923586,
        4.497410728008395,
        3.823803321923586
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "dce53cac-ecdc-4958-879e-432161d074cc": {
      "name": "Bounce",
      "tags": [
        "BouncePad"
      ],
      "enabled": true,
      "resource_id": "dce53cac-ecdc-4958-879e-432161d074cc",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        17.817466735839844,
        0.39114561676979065,
        -45.46453945779492
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.9,
        2.817224769653252,
        2.9
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 29932663,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        },
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2.9,
            0.45,
            2.9
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "d1abd9ac-ade3-428e-be53-2ed121f0761d": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "d1abd9ac-ade3-428e-be53-2ed121f0761d",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "75edbb11-7eaf-4d7e-91f8-72ce649ef5fc"
      ],
      "position": [
        -36.575746543372794,
        10.17876545041925,
        52.03264807575864
      ],
      "rotation": [
        0,
        -42.974161702400274,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018396,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "75edbb11-7eaf-4d7e-91f8-72ce649ef5fc": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic"
      ],
      "enabled": true,
      "resource_id": "75edbb11-7eaf-4d7e-91f8-72ce649ef5fc",
      "parent": "d1abd9ac-ade3-428e-be53-2ed121f0761d",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "4b9fead8-9e5e-4de8-b3e9-2d9a3b2eb771": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "4b9fead8-9e5e-4de8-b3e9-2d9a3b2eb771",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "8d7b253d-559c-4aa0-ab76-4a8cbfdfae3b"
      ],
      "position": [
        15.30256153594626,
        10.178765296936035,
        53.919551849365234
      ],
      "rotation": [
        0,
        -42.974161702400274,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018396,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "8d7b253d-559c-4aa0-ab76-4a8cbfdfae3b": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic"
      ],
      "enabled": true,
      "resource_id": "8d7b253d-559c-4aa0-ab76-4a8cbfdfae3b",
      "parent": "4b9fead8-9e5e-4de8-b3e9-2d9a3b2eb771",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "8d3d7758-7b4d-44a3-a3a9-2ef627b90d2a": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "8d3d7758-7b4d-44a3-a3a9-2ef627b90d2a",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "abad8fb9-2cdd-49cc-8b5e-dbf23b648844"
      ],
      "position": [
        5.882450103759766,
        10.119453430175781,
        36.3976565664426
      ],
      "rotation": [
        0,
        -5.584952414167739,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197280,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "abad8fb9-2cdd-49cc-8b5e-dbf23b648844": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "abad8fb9-2cdd-49cc-8b5e-dbf23b648844",
      "parent": "8d3d7758-7b4d-44a3-a3a9-2ef627b90d2a",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "edaa0f11-05a6-4354-8126-13f28df87e06": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "edaa0f11-05a6-4354-8126-13f28df87e06",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "552f304f-d7ae-423e-b2a0-d78fe5a2c375"
      ],
      "position": [
        5.882450103759766,
        10.119453430175781,
        32.199854634082335
      ],
      "rotation": [
        0,
        -9.54479114814881,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197280,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "552f304f-d7ae-423e-b2a0-d78fe5a2c375": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "552f304f-d7ae-423e-b2a0-d78fe5a2c375",
      "parent": "edaa0f11-05a6-4354-8126-13f28df87e06",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            3
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "bd24997b-b523-47fe-a5da-dcb9eb966780": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "bd24997b-b523-47fe-a5da-dcb9eb966780",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "17a6f42b-ada8-43d6-badd-be524afcaa50"
      ],
      "position": [
        5.521492350253778,
        14.10638427734375,
        36.455909729003906
      ],
      "rotation": [
        0,
        -9.54479114814881,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197285,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "17a6f42b-ada8-43d6-badd-be524afcaa50": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "17a6f42b-ada8-43d6-badd-be524afcaa50",
      "parent": "bd24997b-b523-47fe-a5da-dcb9eb966780",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "c51ffae1-b2bf-4906-866b-dae71b66d235": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "c51ffae1-b2bf-4906-866b-dae71b66d235",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "001bf9ea-b442-4f25-9174-82183de1fc39"
      ],
      "position": [
        5.029216289520264,
        14.10638427734375,
        31.25586306543495
      ],
      "rotation": [
        0,
        5.6609703750875555,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197280,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "001bf9ea-b442-4f25-9174-82183de1fc39": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "001bf9ea-b442-4f25-9174-82183de1fc39",
      "parent": "c51ffae1-b2bf-4906-866b-dae71b66d235",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "eda21872-0772-4912-a5a6-179dfd401780": {
      "name": "pyramid_large",
      "tags": [],
      "enabled": true,
      "resource_id": "eda21872-0772-4912-a5a6-179dfd401780",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -92.0720331102521,
        3.63205309021433e-30,
        -378.7376652756328
      ],
      "rotation": [
        -6.076307229976172e-31,
        40.416455119545,
        1.5492456774632665e-30
      ],
      "scale": [
        14.837060879660257,
        14.837060879660257,
        14.837060879660257
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536015,
          "materialAsset": null,
          "castShadows": false,
          "castShadowsLightmap": false,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "c83f51d1-afb1-4dd1-8dae-2434f29f67a9": {
      "name": "blue",
      "tags": [
        "SpawnPoint"
      ],
      "enabled": true,
      "resource_id": "c83f51d1-afb1-4dd1-8dae-2434f29f67a9",
      "parent": "317a1d13-b11c-4f26-bede-e4324b7cf98a",
      "children": [],
      "position": [
        -62.27925109863281,
        3.3686506710103714,
        -7.319929599761963
      ],
      "rotation": [
        0,
        -89.19389698064406,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "eb73b0c1-6544-4c49-845f-6bdbe8aed68c": {
      "name": "blue",
      "tags": [
        "SpawnPoint"
      ],
      "enabled": true,
      "resource_id": "eb73b0c1-6544-4c49-845f-6bdbe8aed68c",
      "parent": "317a1d13-b11c-4f26-bede-e4324b7cf98a",
      "children": [],
      "position": [
        -70.11865853405232,
        16.259599685668945,
        21.27187156677246
      ],
      "rotation": [
        0,
        -88.13981318383003,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "947d0d94-e323-4b7e-ad79-e1ee14390c05": {
      "name": "blue",
      "tags": [
        "SpawnPoint"
      ],
      "enabled": true,
      "resource_id": "947d0d94-e323-4b7e-ad79-e1ee14390c05",
      "parent": "317a1d13-b11c-4f26-bede-e4324b7cf98a",
      "children": [],
      "position": [
        16.96311562318185,
        13.04420280456543,
        43.080970764160156
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "36c9364f-99eb-4a82-a57d-bd8affecb8be": {
      "name": "blue",
      "tags": [
        "SpawnPoint"
      ],
      "enabled": true,
      "resource_id": "36c9364f-99eb-4a82-a57d-bd8affecb8be",
      "parent": "317a1d13-b11c-4f26-bede-e4324b7cf98a",
      "children": [],
      "position": [
        -30.945396423339844,
        13.04420280456543,
        47.439824205531956
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "6c2a610d-21bd-4a6f-aeb0-1ac89b9a9a33": {
      "name": "red",
      "tags": [
        "SpawnPoint"
      ],
      "enabled": true,
      "resource_id": "6c2a610d-21bd-4a6f-aeb0-1ac89b9a9a33",
      "parent": "317a1d13-b11c-4f26-bede-e4324b7cf98a",
      "children": [],
      "position": [
        -3.4532139326980342,
        14.369325637817383,
        -46.295597076416016
      ],
      "rotation": [
        180,
        -43.71986837344201,
        180
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "673aeddc-4d73-42e5-b7ff-e33e700d497b": {
      "name": "red",
      "tags": [
        "SpawnPoint"
      ],
      "enabled": true,
      "resource_id": "673aeddc-4d73-42e5-b7ff-e33e700d497b",
      "parent": "317a1d13-b11c-4f26-bede-e4324b7cf98a",
      "children": [],
      "position": [
        53.56315612792969,
        15.438798883904944,
        -41.587337493896484
      ],
      "rotation": [
        180,
        19.77988381759203,
        180
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "015a56f0-dba3-47ab-b334-59157214a713": {
      "name": "hallway_1",
      "tags": [],
      "enabled": true,
      "resource_id": "015a56f0-dba3-47ab-b334-59157214a713",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "4d923d2e-2bc5-4872-a160-60653735412c",
        "86960841-4ef1-4d12-addd-9086c10773b2",
        "5acf797d-f535-4846-96e5-e217316d23f2"
      ],
      "position": [
        -77.89702564211656,
        -1.3653812408447266,
        -23.59702048010164
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.899112094338016,
        2.861579718525523,
        3.407250847104039
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30929888,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "4d923d2e-2bc5-4872-a160-60653735412c": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "4d923d2e-2bc5-4872-a160-60653735412c",
      "parent": "015a56f0-dba3-47ab-b334-59157214a713",
      "children": [],
      "position": [
        2.5,
        2.3307621231260267,
        -4.690684887643803e-16
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            1.7,
            6,
            10.8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "86960841-4ef1-4d12-addd-9086c10773b2": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "86960841-4ef1-4d12-addd-9086c10773b2",
      "parent": "015a56f0-dba3-47ab-b334-59157214a713",
      "children": [],
      "position": [
        -2.5,
        2.3307621675776886,
        4.809175992132244e-16
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            1.7,
            6,
            10.8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "5acf797d-f535-4846-96e5-e217316d23f2": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick",
        "Grapple"
      ],
      "enabled": true,
      "resource_id": "5acf797d-f535-4846-96e5-e217316d23f2",
      "parent": "015a56f0-dba3-47ab-b334-59157214a713",
      "children": [],
      "position": [
        0,
        5.544313233836875,
        4.809176204424314e-16
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.5,
            4.2,
            10.8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "79da678c-3b16-4d35-9fb5-197d547e28ec": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "79da678c-3b16-4d35-9fb5-197d547e28ec",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "5bdcfade-cb27-4fe5-a507-76e9edd31f45"
      ],
      "position": [
        -88.23848217888633,
        0,
        -7.605313555207166
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "5bdcfade-cb27-4fe5-a507-76e9edd31f45": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "5bdcfade-cb27-4fe5-a507-76e9edd31f45",
      "parent": "79da678c-3b16-4d35-9fb5-197d547e28ec",
      "children": [],
      "position": [
        -1.553317110492003e-7,
        2.9599057337074033,
        7.334056135732681e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "5f0ae9f4-0fb4-4282-9430-efca4b7c2122": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "5f0ae9f4-0fb4-4282-9430-efca4b7c2122",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "12a3f536-3dac-45f6-bc92-0eff86b2c465"
      ],
      "position": [
        -88.23848217888633,
        0,
        4.494330725287332
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "12a3f536-3dac-45f6-bc92-0eff86b2c465": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "12a3f536-3dac-45f6-bc92-0eff86b2c465",
      "parent": "5f0ae9f4-0fb4-4282-9430-efca4b7c2122",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "6b0efa7b-3901-434f-b805-2b286381df9a": {
      "name": "pillar_round_floor_red",
      "tags": [],
      "enabled": true,
      "resource_id": "6b0efa7b-3901-434f-b805-2b286381df9a",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "1388714b-5cd8-4847-b5b9-341238bd1c3f"
      ],
      "position": [
        -86.46165976284513,
        0,
        3.7676752758744865
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.2106873323164495,
        2.4467209881679985,
        3.2106873323164495
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30844156,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "1388714b-5cd8-4847-b5b9-341238bd1c3f": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "1388714b-5cd8-4847-b5b9-341238bd1c3f",
      "parent": "6b0efa7b-3901-434f-b805-2b286381df9a",
      "children": [],
      "position": [
        5.662551139096195e-8,
        2.195946879445093,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "cylinder",
          "halfExtents": [
            1.51,
            1.51,
            1.51
          ],
          "radius": 2.2,
          "axis": 1,
          "height": 15,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "d6c684a1-ab56-46f1-841a-ae139e5ab8c8": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "d6c684a1-ab56-46f1-841a-ae139e5ab8c8",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "58e1273f-5ab3-43cc-80a2-8d920f91c6b4"
      ],
      "position": [
        -80.42292303917863,
        0,
        6.26878114243334
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "58e1273f-5ab3-43cc-80a2-8d920f91c6b4": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "58e1273f-5ab3-43cc-80a2-8d920f91c6b4",
      "parent": "d6c684a1-ab56-46f1-841a-ae139e5ab8c8",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "00a693c6-fd64-4c02-bacb-7e39cf0a8d87": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "00a693c6-fd64-4c02-bacb-7e39cf0a8d87",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "d9856811-91f0-4e1c-90c2-850b21d7bc53"
      ],
      "position": [
        -88.23848217888633,
        0,
        -38.420460823785795
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "d9856811-91f0-4e1c-90c2-850b21d7bc53": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "d9856811-91f0-4e1c-90c2-850b21d7bc53",
      "parent": "00a693c6-fd64-4c02-bacb-7e39cf0a8d87",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "cd3185f4-cb57-4e68-888e-4022265bb263": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "cd3185f4-cb57-4e68-888e-4022265bb263",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "3a538640-be00-4b88-afd9-79e2cbaa9f83"
      ],
      "position": [
        -88.23848217888633,
        0,
        -50.829706767779825
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "3a538640-be00-4b88-afd9-79e2cbaa9f83": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "3a538640-be00-4b88-afd9-79e2cbaa9f83",
      "parent": "cd3185f4-cb57-4e68-888e-4022265bb263",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "97a12bdb-25f5-4834-b54c-497c8233bcb9": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "97a12bdb-25f5-4834-b54c-497c8233bcb9",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "85aeadfe-8d9f-4780-848c-ad4803aa7d2c"
      ],
      "position": [
        -62.40569648500778,
        0,
        -30.133480111743744
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "85aeadfe-8d9f-4780-848c-ad4803aa7d2c": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "85aeadfe-8d9f-4780-848c-ad4803aa7d2c",
      "parent": "97a12bdb-25f5-4834-b54c-497c8233bcb9",
      "children": [],
      "position": [
        -1.6964952465059469e-7,
        2.048650552917989,
        9.547452464175876e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "006db230-ba94-4eb6-a29c-18bbebe6821a": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "006db230-ba94-4eb6-a29c-18bbebe6821a",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "904e9623-9768-4ff0-a2d5-570c6dce29e6"
      ],
      "position": [
        -80.38349039582718,
        0,
        -54.5300042542254
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "904e9623-9768-4ff0-a2d5-570c6dce29e6": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "904e9623-9768-4ff0-a2d5-570c6dce29e6",
      "parent": "006db230-ba94-4eb6-a29c-18bbebe6821a",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "925664ff-a0fb-4c1a-b01b-4eb0035ff34e": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "925664ff-a0fb-4c1a-b01b-4eb0035ff34e",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "0de89f67-384a-42ed-bdc3-1366f6ea958d"
      ],
      "position": [
        -68.02898418237146,
        0,
        -54.5300042542254
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "0de89f67-384a-42ed-bdc3-1366f6ea958d": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "0de89f67-384a-42ed-bdc3-1366f6ea958d",
      "parent": "925664ff-a0fb-4c1a-b01b-4eb0035ff34e",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "31296035-4097-4f2b-afaa-1c63cf6fb77c": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "31296035-4097-4f2b-afaa-1c63cf6fb77c",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "da1e1488-6e0d-45ee-a057-a2bbfaf2c257"
      ],
      "position": [
        -37.0468496760144,
        5.721083201695968e-15,
        -18.9169921875
      ],
      "rotation": [
        -1.4033418697203106e-14,
        3.975344045709257e-30,
        3.947785528429057e-14
      ],
      "scale": [
        3.982600780221009,
        3.0840293312107256,
        2.9049360745341204
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "da1e1488-6e0d-45ee-a057-a2bbfaf2c257": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "da1e1488-6e0d-45ee-a057-a2bbfaf2c257",
      "parent": "31296035-4097-4f2b-afaa-1c63cf6fb77c",
      "children": [],
      "position": [
        -0.0000034340746424277313,
        1.7617526934961976,
        7.985923730635669e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            7.98,
            7,
            2.95
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "7b0f4bec-14d6-4fd5-a731-006305938406": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "7b0f4bec-14d6-4fd5-a731-006305938406",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "994b0f49-d341-4c40-8f5f-bb5079d65745"
      ],
      "position": [
        -21.52593947458155,
        1.641527834171899e-14,
        -18.9169921875
      ],
      "rotation": [
        -1.4033418697203106e-14,
        3.975344045709257e-30,
        3.947785528429057e-14
      ],
      "scale": [
        3.982600780221009,
        3.0840293312107256,
        2.9049360745341204
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "994b0f49-d341-4c40-8f5f-bb5079d65745": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "994b0f49-d341-4c40-8f5f-bb5079d65745",
      "parent": "7b0f4bec-14d6-4fd5-a731-006305938406",
      "children": [],
      "position": [
        -0.0000034340746424277313,
        1.7617526934961976,
        7.985923730635669e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            7.98,
            7,
            2.95
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "ed8f5360-faac-4431-975e-ba733fc8b3ff": {
      "name": "Ramp",
      "tags": [],
      "enabled": true,
      "resource_id": "ed8f5360-faac-4431-975e-ba733fc8b3ff",
      "parent": "a84eb64b-ae5c-49f9-bb7c-a0746aae0286",
      "children": [
        "5ad9b9f5-012c-446b-854b-e8171369c794",
        "f616b29e-6c81-4cfa-8203-3f2819a29414"
      ],
      "position": [
        -29.062277834766693,
        0,
        0
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "19fcf8e4-3829-4cb8-a69e-145cc0a9eaad": {
      "name": "Ramp",
      "tags": [],
      "enabled": true,
      "resource_id": "19fcf8e4-3829-4cb8-a69e-145cc0a9eaad",
      "parent": "a84eb64b-ae5c-49f9-bb7c-a0746aae0286",
      "children": [
        "f33b4f99-d44e-4d54-9cde-ef0f39f03272",
        "029eaea3-7f5c-4572-bf47-9a0c6d6f9b25"
      ],
      "position": [
        -53.02620278966752,
        2.2390453180260085e-15,
        -49.874480603018206
      ],
      "rotation": [
        180,
        0,
        180
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "f33b4f99-d44e-4d54-9cde-ef0f39f03272": {
      "position": [
        -0.9662908511205579,
        2.548170424919154,
        12.768607284116841
      ],
      "scale": [
        20,
        1,
        20
      ],
      "name": "Ground",
      "parent": "19fcf8e4-3829-4cb8-a69e-145cc0a9eaad",
      "resource_id": "f33b4f99-d44e-4d54-9cde-ef0f39f03272",
      "components": {
        "model": {
          "layers": [
            0
          ],
          "isStatic": false,
          "castShadows": true,
          "castShadowsLightmap": false,
          "lightmapped": false,
          "materialAsset": 29542740,
          "receiveShadows": true,
          "enabled": true,
          "castShadowsLightMap": false,
          "asset": null,
          "type": "plane",
          "lightmapSizeMultiplier": 1,
          "batchGroupId": null
        },
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            10,
            0.01,
            10
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      },
      "rotation": [
        -90.00000113393138,
        -74.99999870487031,
        90.00000032354309
      ],
      "tags": [],
      "enabled": true,
      "children": []
    },
    "029eaea3-7f5c-4572-bf47-9a0c6d6f9b25": {
      "position": [
        -0.9662908511205579,
        7.628909207801844,
        31.730180884885883
      ],
      "scale": [
        20,
        1,
        20
      ],
      "name": "Ground",
      "parent": "19fcf8e4-3829-4cb8-a69e-145cc0a9eaad",
      "resource_id": "029eaea3-7f5c-4572-bf47-9a0c6d6f9b25",
      "components": {
        "model": {
          "layers": [
            0
          ],
          "isStatic": false,
          "castShadows": true,
          "castShadowsLightmap": false,
          "lightmapped": false,
          "materialAsset": 29542740,
          "receiveShadows": true,
          "enabled": true,
          "castShadowsLightMap": false,
          "asset": null,
          "type": "plane",
          "lightmapSizeMultiplier": 1,
          "batchGroupId": null
        },
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            10,
            0.01,
            10
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      },
      "rotation": [
        -90.00000113393138,
        -74.99999870487031,
        90.00000032354309
      ],
      "tags": [],
      "enabled": true,
      "children": []
    },
    "0b96baa0-5e59-4701-be11-a2d11d40e839": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "0b96baa0-5e59-4701-be11-a2d11d40e839",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "eb728c04-c74f-4a50-93bb-56650ea6be16"
      ],
      "position": [
        -41.900822525675544,
        0,
        -50.82970676777983
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "eb728c04-c74f-4a50-93bb-56650ea6be16": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "eb728c04-c74f-4a50-93bb-56650ea6be16",
      "parent": "0b96baa0-5e59-4701-be11-a2d11d40e839",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "eff14bfa-96f5-4206-8ab2-fdb4ac796b6c": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "eff14bfa-96f5-4206-8ab2-fdb4ac796b6c",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "24447591-66be-4a67-9001-a14fd1066296"
      ],
      "position": [
        -45.475134561038274,
        0,
        -39.63288076847994
      ],
      "rotation": [
        180,
        -54.73633960987006,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "24447591-66be-4a67-9001-a14fd1066296": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "24447591-66be-4a67-9001-a14fd1066296",
      "parent": "eff14bfa-96f5-4206-8ab2-fdb4ac796b6c",
      "children": [],
      "position": [
        8.20211198515608e-7,
        2.0865617111812225,
        0.0000024445189410471357
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            7,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "fd87fc48-1404-4ca3-b463-f37114c3957c": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "fd87fc48-1404-4ca3-b463-f37114c3957c",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "f332d5bf-3f28-45fb-952b-424dadaca7d9"
      ],
      "position": [
        -52.23732619083919,
        1.0719158292883305e-15,
        -33.51743503810913
      ],
      "rotation": [
        180,
        -33.633692327145866,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "f332d5bf-3f28-45fb-952b-424dadaca7d9": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "f332d5bf-3f28-45fb-952b-424dadaca7d9",
      "parent": "fd87fc48-1404-4ca3-b463-f37114c3957c",
      "children": [],
      "position": [
        -0.000003902672574440658,
        1.659996566764429,
        -0.0000027025145072911982
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            7,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "2736f6ad-4f0a-400a-b302-ee8db853cf7e": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "2736f6ad-4f0a-400a-b302-ee8db853cf7e",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "59e31eb3-b7b7-4973-90e3-318a97e7ae2f"
      ],
      "position": [
        -41.900822525675544,
        0.8716751087149226,
        -62.88262130068974
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "59e31eb3-b7b7-4973-90e3-318a97e7ae2f": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "59e31eb3-b7b7-4973-90e3-318a97e7ae2f",
      "parent": "2736f6ad-4f0a-400a-b302-ee8db853cf7e",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "d42d7fec-5c48-4eac-bc65-1cbd39018dc8": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "d42d7fec-5c48-4eac-bc65-1cbd39018dc8",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "4dc2df13-e3af-48d0-8c3b-1bf59172b37b"
      ],
      "position": [
        -41.900822525675544,
        4.0356211113035725,
        -75.3427238560906
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "4dc2df13-e3af-48d0-8c3b-1bf59172b37b": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "4dc2df13-e3af-48d0-8c3b-1bf59172b37b",
      "parent": "d42d7fec-5c48-4eac-bc65-1cbd39018dc8",
      "children": [],
      "position": [
        5.662551139096195e-8,
        2.2222779427494923,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "08f67bd7-d800-4474-825e-65d372f79382": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "08f67bd7-d800-4474-825e-65d372f79382",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "315f8079-33ce-4d01-8ae1-6d0cdb1ea483"
      ],
      "position": [
        -41.900822525675544,
        7.17968197515008,
        -87.5601423913088
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "315f8079-33ce-4d01-8ae1-6d0cdb1ea483": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "315f8079-33ce-4d01-8ae1-6d0cdb1ea483",
      "parent": "08f67bd7-d800-4474-825e-65d372f79382",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "41402653-f08d-45d6-8ac6-7884eb3a8a0c": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "41402653-f08d-45d6-8ac6-7884eb3a8a0c",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "cef686dc-5d65-46d9-babe-900c6a644081"
      ],
      "position": [
        -63.734296376431786,
        7.17968197515008,
        -87.5601423913088
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "cef686dc-5d65-46d9-babe-900c6a644081": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "cef686dc-5d65-46d9-babe-900c6a644081",
      "parent": "41402653-f08d-45d6-8ac6-7884eb3a8a0c",
      "children": [],
      "position": [
        -9.525358599660194e-7,
        2.8648496754955177,
        5.401215474876153e-8
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "1515f39a-ad0b-4c86-8e35-373cebd7b10c": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "1515f39a-ad0b-4c86-8e35-373cebd7b10c",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "8124ad31-d201-463d-8954-4f459d10fcee"
      ],
      "position": [
        -63.734296376431786,
        4.0356211113035725,
        -75.3427238560906
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "8124ad31-d201-463d-8954-4f459d10fcee": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "8124ad31-d201-463d-8954-4f459d10fcee",
      "parent": "1515f39a-ad0b-4c86-8e35-373cebd7b10c",
      "children": [],
      "position": [
        5.662551139096195e-8,
        3.818098417845165,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "7cabc6b6-c813-4535-a2df-d1c5c084245a": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "7cabc6b6-c813-4535-a2df-d1c5c084245a",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "929d9d03-e98e-45f1-b993-5c227853aaad"
      ],
      "position": [
        -63.734296376431786,
        0.8716751087149226,
        -62.882621300689735
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "929d9d03-e98e-45f1-b993-5c227853aaad": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "929d9d03-e98e-45f1-b993-5c227853aaad",
      "parent": "7cabc6b6-c813-4535-a2df-d1c5c084245a",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "6741e083-782f-4c48-bcd9-ee7dea0f6f98": {
      "position": [
        20.93535033205599,
        12.39,
        -63.60277710038505
      ],
      "scale": [
        20,
        1,
        20
      ],
      "name": "Ground",
      "parent": "a84eb64b-ae5c-49f9-bb7c-a0746aae0286",
      "resource_id": "6741e083-782f-4c48-bcd9-ee7dea0f6f98",
      "components": {
        "model": {
          "layers": [
            0
          ],
          "isStatic": false,
          "castShadows": true,
          "castShadowsLightmap": false,
          "lightmapped": false,
          "materialAsset": 29542740,
          "receiveShadows": true,
          "enabled": true,
          "castShadowsLightMap": false,
          "asset": null,
          "type": "plane",
          "lightmapSizeMultiplier": 1,
          "batchGroupId": null
        },
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            10,
            0.01,
            10
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      },
      "rotation": [
        0,
        0,
        0
      ],
      "tags": [
        "Dirt"
      ],
      "enabled": true,
      "children": []
    },
    "9fe946be-a40e-4ea9-8527-c7b127b0bad8": {
      "position": [
        20.93535033205599,
        11.212041694614566,
        -83.52653960531251
      ],
      "scale": [
        20,
        1,
        20
      ],
      "name": "Ground",
      "parent": "a84eb64b-ae5c-49f9-bb7c-a0746aae0286",
      "resource_id": "9fe946be-a40e-4ea9-8527-c7b127b0bad8",
      "components": {
        "model": {
          "layers": [
            0
          ],
          "isStatic": false,
          "castShadows": true,
          "castShadowsLightmap": false,
          "lightmapped": false,
          "materialAsset": 29542740,
          "receiveShadows": true,
          "enabled": true,
          "castShadowsLightMap": false,
          "asset": null,
          "type": "plane",
          "lightmapSizeMultiplier": 1,
          "batchGroupId": null
        },
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            10,
            0.01,
            10
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      },
      "rotation": [
        -6.756049282367337,
        0,
        0
      ],
      "tags": [
        "Dirt"
      ],
      "enabled": true,
      "children": []
    },
    "32381034-5b60-4e6a-a321-186500eb80cb": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "32381034-5b60-4e6a-a321-186500eb80cb",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -63.734296376431786,
        10.143437444051669,
        -100.03207282050266
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "2355f32d-0f96-4057-a24c-8081bacb437d": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "2355f32d-0f96-4057-a24c-8081bacb437d",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "7e5c5b57-9a45-4bf9-8f01-9f21e2e652fd"
      ],
      "position": [
        -63.734296376431786,
        10.143437444051669,
        -112.50810639225182
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "7e5c5b57-9a45-4bf9-8f01-9f21e2e652fd": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "7e5c5b57-9a45-4bf9-8f01-9f21e2e652fd",
      "parent": "2355f32d-0f96-4057-a24c-8081bacb437d",
      "children": [],
      "position": [
        -0.7846586813905247,
        1.5727348087098107,
        5.401215119604785e-8
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            20,
            15,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "46be8fca-ee06-4ae8-9ff8-30fd8e2e8c0d": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "46be8fca-ee06-4ae8-9ff8-30fd8e2e8c0d",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "e24c31cf-ba5a-4614-abb5-a487e1297977"
      ],
      "position": [
        -55.22142087800925,
        10.143437444051667,
        -112.5463165373722
      ],
      "rotation": [
        180,
        0,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "e24c31cf-ba5a-4614-abb5-a487e1297977": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "e24c31cf-ba5a-4614-abb5-a487e1297977",
      "parent": "46be8fca-ee06-4ae8-9ff8-30fd8e2e8c0d",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "98761754-edbb-4945-b71b-0332cc61b5b0": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "98761754-edbb-4945-b71b-0332cc61b5b0",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "e218e29a-6546-4fd1-ae14-76ef8406a166"
      ],
      "position": [
        30.17173293358838,
        10.143437444051655,
        -112.5463165373722
      ],
      "rotation": [
        180,
        0,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "e218e29a-6546-4fd1-ae14-76ef8406a166": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "e218e29a-6546-4fd1-ae14-76ef8406a166",
      "parent": "98761754-edbb-4945-b71b-0332cc61b5b0",
      "children": [],
      "position": [
        5.662551139096195e-8,
        3.0500587431667783,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "7ffc593d-2601-40f7-914e-4eba66594ccc": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "7ffc593d-2601-40f7-914e-4eba66594ccc",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "3dd3f165-dfae-4852-991f-027e7d20ad0d"
      ],
      "position": [
        5.946755822329601,
        10.143437444051656,
        -89.13193444854637
      ],
      "rotation": [
        180,
        0,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "3dd3f165-dfae-4852-991f-027e7d20ad0d": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "3dd3f165-dfae-4852-991f-027e7d20ad0d",
      "parent": "7ffc593d-2601-40f7-914e-4eba66594ccc",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "28c27597-010d-403b-a465-1e39939a9faa": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "28c27597-010d-403b-a465-1e39939a9faa",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "169ccb81-b144-45a6-bb89-0d53928146f5"
      ],
      "position": [
        -1.3078234337120076,
        10.143437444051658,
        -91.87210503889138
      ],
      "rotation": [
        180,
        0,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "169ccb81-b144-45a6-bb89-0d53928146f5": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "169ccb81-b144-45a6-bb89-0d53928146f5",
      "parent": "28c27597-010d-403b-a465-1e39939a9faa",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "4bffc924-e9e0-4fed-a2d0-da90e74c8266": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "4bffc924-e9e0-4fed-a2d0-da90e74c8266",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "7702a1dd-7208-4aba-8f96-4c714efda706"
      ],
      "position": [
        -13.640727402218808,
        10.14343744405166,
        -91.87210503889138
      ],
      "rotation": [
        180,
        0,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "7702a1dd-7208-4aba-8f96-4c714efda706": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "7702a1dd-7208-4aba-8f96-4c714efda706",
      "parent": "4bffc924-e9e0-4fed-a2d0-da90e74c8266",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "b4787ecd-cf6c-40d3-a60a-bfab4ecdd43a": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "b4787ecd-cf6c-40d3-a60a-bfab4ecdd43a",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "9b5c90c6-3d72-415a-8ca5-64283925d92c"
      ],
      "position": [
        -26.117410173189114,
        10.143437444051662,
        -91.87210503889138
      ],
      "rotation": [
        180,
        0,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "9b5c90c6-3d72-415a-8ca5-64283925d92c": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "9b5c90c6-3d72-415a-8ca5-64283925d92c",
      "parent": "b4787ecd-cf6c-40d3-a60a-bfab4ecdd43a",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "26ff3a19-04bd-4c65-ab31-7845008a7d88": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "26ff3a19-04bd-4c65-ab31-7845008a7d88",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "e8e3d643-169e-4423-a971-8495bd182a28"
      ],
      "position": [
        -38.56689835513636,
        10.143437444051663,
        -91.87210503889138
      ],
      "rotation": [
        180,
        0,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "e8e3d643-169e-4423-a971-8495bd182a28": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "e8e3d643-169e-4423-a971-8495bd182a28",
      "parent": "26ff3a19-04bd-4c65-ab31-7845008a7d88",
      "children": [],
      "position": [
        7.582042371723219e-7,
        2.446423302197288,
        -0.0000027141268219565973
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "d0676ba9-d9a8-41db-8a8c-cc87676ffdc9": {
      "name": "hallway_1",
      "tags": [],
      "enabled": true,
      "resource_id": "d0676ba9-d9a8-41db-8a8c-cc87676ffdc9",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "d5b5a61d-a9b4-42cc-b393-49c90b5fd83a",
        "d0b8c96c-fca8-453e-a611-047586481691",
        "3affa2fa-aa05-4f88-84cc-42cc1a653f8e"
      ],
      "position": [
        20.336192767616208,
        11.269820028826302,
        -63.59926781989211
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.899112094338016,
        2.861579718525523,
        3.407250847104039
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30929888,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "d5b5a61d-a9b4-42cc-b393-49c90b5fd83a": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "d5b5a61d-a9b4-42cc-b393-49c90b5fd83a",
      "parent": "d0676ba9-d9a8-41db-8a8c-cc87676ffdc9",
      "children": [],
      "position": [
        2.5,
        2.3307621231260267,
        -4.690684887643803e-16
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            1.7,
            6,
            10.8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "d0b8c96c-fca8-453e-a611-047586481691": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "d0b8c96c-fca8-453e-a611-047586481691",
      "parent": "d0676ba9-d9a8-41db-8a8c-cc87676ffdc9",
      "children": [],
      "position": [
        -2.5,
        2.3307621675776886,
        4.809175992132244e-16
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            1.7,
            6,
            10.8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "3affa2fa-aa05-4f88-84cc-42cc1a653f8e": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick",
        "Grapple"
      ],
      "enabled": true,
      "resource_id": "3affa2fa-aa05-4f88-84cc-42cc1a653f8e",
      "parent": "d0676ba9-d9a8-41db-8a8c-cc87676ffdc9",
      "children": [],
      "position": [
        0,
        5.544313233836875,
        4.809176204424314e-16
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.5,
            4.2,
            10.8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "6571cf1e-0f64-4499-ae47-e84b9a48fd0b": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "6571cf1e-0f64-4499-ae47-e84b9a48fd0b",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "6c21ab41-4ae8-44b2-ae7b-99bc8237cf77"
      ],
      "position": [
        10.291219158539196,
        10.143437444051655,
        -84.94356509340928
      ],
      "rotation": [
        180,
        90,
        179.99999999999997
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "6c21ab41-4ae8-44b2-ae7b-99bc8237cf77": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "6c21ab41-4ae8-44b2-ae7b-99bc8237cf77",
      "parent": "6571cf1e-0f64-4499-ae47-e84b9a48fd0b",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            9,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "b8486825-7c9b-4941-a84a-f01cacb6158c": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "b8486825-7c9b-4941-a84a-f01cacb6158c",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "68efd61a-8dfc-4322-b0e4-90b774f2d52f"
      ],
      "position": [
        10.291219158539198,
        10.143437444051655,
        -72.55497991632922
      ],
      "rotation": [
        180,
        90,
        179.99999999999997
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "68efd61a-8dfc-4322-b0e4-90b774f2d52f": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "68efd61a-8dfc-4322-b0e4-90b774f2d52f",
      "parent": "b8486825-7c9b-4941-a84a-f01cacb6158c",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            9,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "3dcaff7c-7eac-4230-94cf-01604d895924": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "3dcaff7c-7eac-4230-94cf-01604d895924",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "478491d0-4912-4dd0-892d-2b15ce9bbe9b"
      ],
      "position": [
        30.31707353230035,
        10.143437444051646,
        -72.55497991632922
      ],
      "rotation": [
        180,
        90,
        179.99999999999997
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "478491d0-4912-4dd0-892d-2b15ce9bbe9b": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "478491d0-4912-4dd0-892d-2b15ce9bbe9b",
      "parent": "3dcaff7c-7eac-4230-94cf-01604d895924",
      "children": [],
      "position": [
        5.662551139096195e-8,
        1.5727347268188758,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            9,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "179934aa-a9b0-4a59-82ff-5a95dd7b949a": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "179934aa-a9b0-4a59-82ff-5a95dd7b949a",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "cc43eea1-14a8-4936-97a4-af91814c66fb"
      ],
      "position": [
        30.31707353230035,
        10.143437444051646,
        -85.06545626354495
      ],
      "rotation": [
        180,
        90,
        179.99999999999997
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "cc43eea1-14a8-4936-97a4-af91814c66fb": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "cc43eea1-14a8-4936-97a4-af91814c66fb",
      "parent": "179934aa-a9b0-4a59-82ff-5a95dd7b949a",
      "children": [],
      "position": [
        8.795816448525784e-7,
        3.2166107501066517,
        -4.751649740342145e-9
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "fc74e726-1791-4c70-8a35-b525e347f416": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "fc74e726-1791-4c70-8a35-b525e347f416",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "5afbc862-ab8c-40bb-96f3-33d5b5168050"
      ],
      "position": [
        34.84006450070087,
        10.143437444051644,
        -95.81292188857961
      ],
      "rotation": [
        180,
        90,
        179.99999999999997
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "5afbc862-ab8c-40bb-96f3-33d5b5168050": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "5afbc862-ab8c-40bb-96f3-33d5b5168050",
      "parent": "fc74e726-1791-4c70-8a35-b525e347f416",
      "children": [],
      "position": [
        5.662551139096195e-8,
        3.6202942930855033,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "3b522033-f114-4e10-8dec-d0a0e6904b3e": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "3b522033-f114-4e10-8dec-d0a0e6904b3e",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "87e6d1cb-6536-443a-b658-1bfc69d23d4d"
      ],
      "position": [
        34.84006450070087,
        10.143437444051644,
        -108.25662915093896
      ],
      "rotation": [
        180,
        90,
        179.99999999999997
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "87e6d1cb-6536-443a-b658-1bfc69d23d4d": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "87e6d1cb-6536-443a-b658-1bfc69d23d4d",
      "parent": "3b522033-f114-4e10-8dec-d0a0e6904b3e",
      "children": [],
      "position": [
        5.662551139096195e-8,
        3.027329683506864,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "5aee3488-71d5-4a35-867d-159e42819723": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "5aee3488-71d5-4a35-867d-159e42819723",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -4.776118824722088,
        17.19612208882611,
        -88.34070440550055
      ],
      "rotation": [
        0,
        4.669001478714261,
        0
      ],
      "scale": [
        2.6616259368859194,
        3.1305022865230265,
        2.6616259368859194
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "418f146b-5ee7-4077-8a4e-86011b1ead40": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "418f146b-5ee7-4077-8a4e-86011b1ead40",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -37.81145089300406,
        12.538204189372916,
        -85.98377155816236
      ],
      "rotation": [
        0,
        70.61616131819922,
        0
      ],
      "scale": [
        2.6616259368859194,
        3.1305022865230265,
        2.6616259368859194
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "3a195ed7-71c7-4b20-9d86-9c83c010b7ca": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "3a195ed7-71c7-4b20-9d86-9c83c010b7ca",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -40.150976135829126,
        8.935033628837177,
        -44.92338349371329
      ],
      "rotation": [
        0,
        70.61616131819922,
        0
      ],
      "scale": [
        2.6616259368859194,
        3.1305022865230265,
        2.6616259368859194
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "5248ae10-aad9-488e-ae97-58e33ad161ad": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "5248ae10-aad9-488e-ae97-58e33ad161ad",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -67.10787656595387,
        8.935033628837177,
        -59.11956868032022
      ],
      "rotation": [
        0,
        -89.3990528328366,
        0
      ],
      "scale": [
        2.6616259368859194,
        3.1305022865230265,
        2.6616259368859194
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "8b7751c4-49d6-492e-ae40-30ca6f5c8524": {
      "name": "building_base_block3",
      "tags": [],
      "enabled": true,
      "resource_id": "8b7751c4-49d6-492e-ae40-30ca6f5c8524",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -14.990545272827148,
        6.2958550453186035,
        -71.56096992082098
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        9.55756456039625,
        3.453895003323346,
        7.7213883331512445
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30883287,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "a6b4e0d5-8149-4668-824b-bab2a387ef5f": {
      "name": "Village",
      "tags": [],
      "enabled": true,
      "resource_id": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "e2431734-c737-41d3-b0ab-7174d3966aa7",
        "2de6e3e4-987b-43a1-b6aa-64babd81f36a",
        "0998955e-bab1-42b0-99ed-128800babf3a",
        "36565ae1-cd9c-4c07-95b2-8732b7664e4b",
        "430086a1-6664-43c9-bcdb-58b821ef4331",
        "c997ea5f-51e7-4b79-bb00-c5b93103b7bb",
        "81d784da-0eff-46fc-807e-00119be4b78e",
        "8d500fca-f0ad-4b0f-b8a9-4f4bad4b767d",
        "fd1bbd3c-de3e-41d3-9219-424dd039166c",
        "ad4b2662-7f31-4b6b-a6bb-45a088fa669e",
        "e0014748-89b4-4964-b2ef-3a85a109d865",
        "8df1919c-4e75-4d19-8b78-ebade8a40467",
        "443150fa-4e5e-4a29-8a08-49c90f74592a",
        "f8394b53-cd59-4e03-a92e-883ca92b94d7",
        "6bb3e0d9-6575-4090-aca4-9d4838fb96c9",
        "6944a160-70c6-4e36-a64c-30e5413ac354",
        "6eba1617-c02d-44e7-bba7-ede21b07308a"
      ],
      "position": [
        0,
        10.304971256104537,
        -112.83237143997944
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "81d784da-0eff-46fc-807e-00119be4b78e": {
      "name": "scaffolding_1x2_wall_mounted",
      "tags": [],
      "enabled": true,
      "resource_id": "81d784da-0eff-46fc-807e-00119be4b78e",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [],
      "position": [
        -36.443756103515625,
        10.612516403198242,
        50.39128886216597
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        4.102322486480364,
        4.102322486480364,
        4.102322486480364
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30883305,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "8d500fca-f0ad-4b0f-b8a9-4f4bad4b767d": {
      "name": "scaffolding_1x2_wall_mounted",
      "tags": [],
      "enabled": true,
      "resource_id": "8d500fca-f0ad-4b0f-b8a9-4f4bad4b767d",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [],
      "position": [
        -36.443755458479075,
        15.95186416822714,
        36.683869034196505
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        4.102322486480364,
        4.102322486480364,
        4.102322486480364
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30883305,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "fd1bbd3c-de3e-41d3-9219-424dd039166c": {
      "name": "scaffolding_1x2_wall_mounted",
      "tags": [],
      "enabled": true,
      "resource_id": "fd1bbd3c-de3e-41d3-9219-424dd039166c",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [],
      "position": [
        -16.536594347785197,
        15.951864168227138,
        24.214652217965153
      ],
      "rotation": [
        180,
        0,
        180
      ],
      "scale": [
        4.102322486480364,
        4.102322486480364,
        4.102322486480364
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30883305,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "e0014748-89b4-4964-b2ef-3a85a109d865": {
      "name": "well",
      "tags": [],
      "enabled": true,
      "resource_id": "e0014748-89b4-4964-b2ef-3a85a109d865",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [
        "a101c30a-080e-4448-bd66-9339d32cb524",
        "60066449-f3f4-4bf7-842a-312e3004215f",
        "72ad3b44-3b9a-4278-9271-f880e732e5bf"
      ],
      "position": [
        -11.58887767791748,
        -0.20285334673096322,
        -7.263753196421945
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        4.497719349798765,
        3.5334476935632715,
        4.497719349798765
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30883585,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "8df1919c-4e75-4d19-8b78-ebade8a40467": {
      "name": "building_base_block3",
      "tags": [],
      "enabled": true,
      "resource_id": "8df1919c-4e75-4d19-8b78-ebade8a40467",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [],
      "position": [
        31.244953066652126,
        0,
        -13.372610256387034
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.000925918548337,
        3.000925918548337,
        3.000925918548337
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30883287,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100009
        }
      }
    },
    "8acaa78b-8273-4a0e-96aa-d9a417ae8ef0": {
      "name": "arch_1_shade_1",
      "tags": [],
      "enabled": true,
      "resource_id": "8acaa78b-8273-4a0e-96aa-d9a417ae8ef0",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "13bbd171-0ae0-4122-9cc2-c192775d611d",
        "152cfc84-a9e1-4e94-8e0a-e723cf86286e",
        "6b4d7d3d-38de-4035-8802-3e6572c0d7ab"
      ],
      "position": [
        -53.154129562107265,
        5.04302919060592,
        -93.95661653062535
      ],
      "rotation": [
        180,
        0,
        -180
      ],
      "scale": [
        7.525091683243699,
        7.686463391639226,
        6.185641263332534
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018389,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "13bbd171-0ae0-4122-9cc2-c192775d611d": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "13bbd171-0ae0-4122-9cc2-c192775d611d",
      "parent": "8acaa78b-8273-4a0e-96aa-d9a417ae8ef0",
      "children": [],
      "position": [
        0.9970444971580528,
        1.5727347268188758,
        -0.00646220957209918
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2.8,
            8,
            2.22
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "152cfc84-a9e1-4e94-8e0a-e723cf86286e": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "152cfc84-a9e1-4e94-8e0a-e723cf86286e",
      "parent": "8acaa78b-8273-4a0e-96aa-d9a417ae8ef0",
      "children": [],
      "position": [
        -0.9998505064297214,
        1.5727347268188758,
        -0.00646220957209918
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2.8,
            8,
            2.22
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "012b26c2-273b-4cfc-833d-e3eb2977e985": {
      "name": "Waterfall",
      "tags": [],
      "enabled": true,
      "resource_id": "012b26c2-273b-4cfc-833d-e3eb2977e985",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "ea5ac469-28d3-438a-b6be-cc54957a87ed",
        "8a19077b-62dc-4f5c-8384-1ec76be7a4ff"
      ],
      "position": [
        -3.843992233276367,
        11.697053353935285,
        38.25722366141698
      ],
      "rotation": [
        90.00000000000009,
        81.21591943883402,
        90.00000000000009
      ],
      "scale": [
        2.528239963477378,
        4.381516639314331,
        4.381516639314331
      ],
      "components": {
        "sound": {
          "enabled": true,
          "volume": 1,
          "pitch": 1,
          "positional": true,
          "refDistance": 3,
          "maxDistance": 10000,
          "rollOffFactor": 1,
          "distanceModel": "exponential",
          "slots": {
            "1": {
              "name": "Waterfall",
              "loop": true,
              "autoPlay": true,
              "overlap": false,
              "asset": 30975155,
              "startTime": 0,
              "duration": null,
              "volume": 1,
              "pitch": 1
            }
          }
        },
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30978142,
          "materialAsset": null,
          "castShadows": false,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        },
        "script": {
          "enabled": true,
          "order": [
            "waterfall"
          ],
          "scripts": {
            "waterfall": {
              "enabled": true,
              "attributes": {
                "noise_1": 30978140,
                "noise_2": 30978141,
                "top_light_color": [
                  0.4235294117647059,
                  0.6627450980392157,
                  1,
                  1
                ],
                "top_dark_color": [
                  0.34509803921568627,
                  0.49019607843137253,
                  0.6862745098039216,
                  1
                ],
                "bot_light_color": [
                  0.7098039215686275,
                  0.7098039215686275,
                  0.7098039215686275,
                  1
                ],
                "bot_dark_color": [
                  1,
                  1,
                  1,
                  1
                ],
                "speed": 2,
                "opacitySpeed": 1.1
              }
            }
          }
        }
      }
    },
    "ea5ac469-28d3-438a-b6be-cc54957a87ed": {
      "name": "ramp_straight_shade_4",
      "tags": [],
      "enabled": true,
      "resource_id": "ea5ac469-28d3-438a-b6be-cc54957a87ed",
      "parent": "012b26c2-273b-4cfc-833d-e3eb2977e985",
      "children": [],
      "position": [
        -0.9722829160233317,
        3.9907661402130064,
        1.2254530297758357
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        0.3507568242713148,
        1
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30028242,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "8a19077b-62dc-4f5c-8384-1ec76be7a4ff": {
      "name": "ramp_straight_shade_4",
      "tags": [],
      "enabled": true,
      "resource_id": "8a19077b-62dc-4f5c-8384-1ec76be7a4ff",
      "parent": "012b26c2-273b-4cfc-833d-e3eb2977e985",
      "children": [],
      "position": [
        -0.9722829160233317,
        3.9907661402130064,
        -1.3339047465021276
      ],
      "rotation": [
        -180,
        0,
        -180
      ],
      "scale": [
        1,
        0.3507568242713148,
        1
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30028242,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "aa5d5ef8-2e97-4bcf-b6bb-077387e001cc": {
      "name": "Modes",
      "tags": [],
      "enabled": true,
      "resource_id": "aa5d5ef8-2e97-4bcf-b6bb-077387e001cc",
      "parent": "6d984d2f-ab17-42b9-b521-7b1bfb7da4ca",
      "children": [
        "2e46b332-52e4-4306-8988-266c15147fb6"
      ],
      "position": [
        0,
        0,
        0
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "2e46b332-52e4-4306-8988-266c15147fb6": {
      "name": "POINT",
      "tags": [],
      "enabled": true,
      "resource_id": "2e46b332-52e4-4306-8988-266c15147fb6",
      "parent": "aa5d5ef8-2e97-4bcf-b6bb-077387e001cc",
      "children": [
        "7b23c9f1-ed85-4383-addc-f20cd3af6256",
        "f80861f3-47d6-4af1-9cfc-24b68b6f54f3",
        "fe969e5a-1c80-4b96-81f6-982f06c9beca",
        "b627896c-8a71-4c6c-95be-caa68b70093e",
        "7abb6660-5e87-466f-9d8b-5d9f85fea7ed"
      ],
      "position": [
        0,
        0,
        0
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "7b23c9f1-ed85-4383-addc-f20cd3af6256": {
      "name": "Objective",
      "tags": [
        "Objective"
      ],
      "enabled": true,
      "resource_id": "7b23c9f1-ed85-4383-addc-f20cd3af6256",
      "parent": "2e46b332-52e4-4306-8988-266c15147fb6",
      "children": [],
      "position": [
        0,
        0,
        -1.789
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "f80861f3-47d6-4af1-9cfc-24b68b6f54f3": {
      "name": "Objective",
      "tags": [
        "Objective"
      ],
      "enabled": true,
      "resource_id": "f80861f3-47d6-4af1-9cfc-24b68b6f54f3",
      "parent": "2e46b332-52e4-4306-8988-266c15147fb6",
      "children": [],
      "position": [
        -59.946,
        0,
        -42.791
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "fe969e5a-1c80-4b96-81f6-982f06c9beca": {
      "name": "Objective",
      "tags": [
        "Objective"
      ],
      "enabled": true,
      "resource_id": "fe969e5a-1c80-4b96-81f6-982f06c9beca",
      "parent": "2e46b332-52e4-4306-8988-266c15147fb6",
      "children": [],
      "position": [
        -27.031,
        10.229,
        -110.758
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "b627896c-8a71-4c6c-95be-caa68b70093e": {
      "name": "Objective",
      "tags": [
        "Objective"
      ],
      "enabled": true,
      "resource_id": "b627896c-8a71-4c6c-95be-caa68b70093e",
      "parent": "2e46b332-52e4-4306-8988-266c15147fb6",
      "children": [],
      "position": [
        49.464,
        14.266,
        -22.157
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "7abb6660-5e87-466f-9d8b-5d9f85fea7ed": {
      "name": "Objective",
      "tags": [
        "Objective"
      ],
      "enabled": true,
      "resource_id": "7abb6660-5e87-466f-9d8b-5d9f85fea7ed",
      "parent": "2e46b332-52e4-4306-8988-266c15147fb6",
      "children": [],
      "position": [
        13.383,
        0,
        18.154
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "a36ea639-f681-4c2f-9424-20f09e841194": {
      "position": [
        -29.10548406987447,
        10.199999809265137,
        51.3835563659668
      ],
      "scale": [
        20,
        1,
        20
      ],
      "name": "Ground",
      "parent": "a84eb64b-ae5c-49f9-bb7c-a0746aae0286",
      "resource_id": "a36ea639-f681-4c2f-9424-20f09e841194",
      "components": {
        "model": {
          "layers": [
            0
          ],
          "isStatic": false,
          "castShadows": true,
          "castShadowsLightmap": false,
          "lightmapped": false,
          "materialAsset": 29542740,
          "receiveShadows": true,
          "enabled": true,
          "castShadowsLightMap": false,
          "asset": null,
          "type": "plane",
          "lightmapSizeMultiplier": 1,
          "batchGroupId": null
        },
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            10,
            0.01,
            10
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      },
      "rotation": [
        0,
        0,
        0
      ],
      "tags": [
        "Dirt"
      ],
      "enabled": true,
      "children": []
    },
    "183e2094-9acc-464e-adc0-06dc18fdbecc": {
      "position": [
        -9.418604850769043,
        10.2,
        -158.7
      ],
      "scale": [
        135,
        0.27551477592180323,
        135
      ],
      "name": "Ground",
      "parent": "a84eb64b-ae5c-49f9-bb7c-a0746aae0286",
      "resource_id": "183e2094-9acc-464e-adc0-06dc18fdbecc",
      "components": {
        "model": {
          "layers": [
            0
          ],
          "isStatic": false,
          "castShadows": true,
          "castShadowsLightmap": false,
          "lightmapped": false,
          "materialAsset": 31300322,
          "receiveShadows": true,
          "enabled": true,
          "castShadowsLightMap": false,
          "asset": null,
          "type": "plane",
          "lightmapSizeMultiplier": 1,
          "batchGroupId": null
        },
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            67.5,
            0.01,
            67.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        },
        "script": {
          "enabled": true,
          "order": [
            "terrain"
          ],
          "scripts": {
            "terrain": {
              "enabled": true,
              "attributes": {
                "map": 31300290,
                "red": 30867252,
                "green": 30479676,
                "blue": 30867280,
                "redScale": [
                  30,
                  30
                ],
                "greenScale": [
                  30,
                  30
                ],
                "blueScale": [
                  15,
                  15
                ]
              }
            }
          }
        }
      },
      "rotation": [
        0,
        0,
        0
      ],
      "tags": [
        "Dirt"
      ],
      "enabled": true,
      "children": []
    },
    "a101c30a-080e-4448-bd66-9339d32cb524": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "a101c30a-080e-4448-bd66-9339d32cb524",
      "parent": "e0014748-89b4-4964-b2ef-3a85a109d865",
      "children": [],
      "position": [
        -3.8785870515312126e-8,
        0.21776942097531737,
        0.0000026656229010768584
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "cylinder",
          "halfExtents": [
            6.3,
            6,
            2.5
          ],
          "radius": 3.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "60066449-f3f4-4bf7-842a-312e3004215f": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "60066449-f3f4-4bf7-842a-312e3004215f",
      "parent": "e0014748-89b4-4964-b2ef-3a85a109d865",
      "children": [],
      "position": [
        0.5036501044461956,
        1.3368565354300017,
        0.000007754465059406357
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            0.35,
            4,
            0.35
          ],
          "radius": 3.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "72ad3b44-3b9a-4278-9271-f880e732e5bf": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "72ad3b44-3b9a-4278-9271-f880e732e5bf",
      "parent": "e0014748-89b4-4964-b2ef-3a85a109d865",
      "children": [],
      "position": [
        -0.5029328206065626,
        1.3368565354300017,
        0.000009450745778849523
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            0.35,
            4,
            0.35
          ],
          "radius": 3.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "6bb3e0d9-6575-4090-aca4-9d4838fb96c9": {
      "name": "building_base_block7",
      "tags": [],
      "enabled": true,
      "resource_id": "6bb3e0d9-6575-4090-aca4-9d4838fb96c9",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [
        "23737c7b-5446-4e9f-851c-8097e8c76e0d",
        "c317bb0d-0fa3-45a2-933e-0b3d542644e1",
        "005c6246-ec2c-421a-98b3-2bf0883bb839",
        "90d136f2-22f0-4943-90bc-4056ceca0921",
        "b5949fc0-6b75-48f7-a419-2368ef7d5a0d",
        "e3a30cb7-e6a6-4e46-a027-410c16b352df"
      ],
      "position": [
        -57.34147644042969,
        -0.19701503990087943,
        -12.090736389160156
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        2.6445208631980615,
        2.6445208631980615,
        2.6445208631980615
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 29699871,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100009
        }
      }
    },
    "23737c7b-5446-4e9f-851c-8097e8c76e0d": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "23737c7b-5446-4e9f-851c-8097e8c76e0d",
      "parent": "6bb3e0d9-6575-4090-aca4-9d4838fb96c9",
      "children": [],
      "position": [
        1.1852543618747404,
        1.1663351649280855,
        0.9835100550188756
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            7.5,
            5,
            8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "c317bb0d-0fa3-45a2-933e-0b3d542644e1": {
      "name": "awning_2_hue1",
      "tags": [],
      "enabled": true,
      "resource_id": "c317bb0d-0fa3-45a2-933e-0b3d542644e1",
      "parent": "6bb3e0d9-6575-4090-aca4-9d4838fb96c9",
      "children": [],
      "position": [
        4.06938580791223,
        5.312000439516851e-8,
        1.1022024905039416
      ],
      "rotation": [
        180,
        90,
        180
      ],
      "scale": [
        1,
        1,
        1.5705831544250461
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 29700053,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100010
        }
      }
    },
    "e2431734-c737-41d3-b0ab-7174d3966aa7": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "e2431734-c737-41d3-b0ab-7174d3966aa7",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [
        "9eb238b4-a3e2-4c80-a575-ae5944429414"
      ],
      "position": [
        -12.854327201843262,
        -0.1259450912475586,
        1.9635660851492815
      ],
      "rotation": [
        0,
        -5.584952442418447,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197280,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "9eb238b4-a3e2-4c80-a575-ae5944429414": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "9eb238b4-a3e2-4c80-a575-ae5944429414",
      "parent": "e2431734-c737-41d3-b0ab-7174d3966aa7",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "36565ae1-cd9c-4c07-95b2-8732b7664e4b": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "36565ae1-cd9c-4c07-95b2-8732b7664e4b",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [
        "224523c9-a087-4bef-a75b-617f77b23cb4"
      ],
      "position": [
        -43.168723734049784,
        -0.1259450912475586,
        -20.42603302001953
      ],
      "rotation": [
        0,
        -5.584952442418447,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197280,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "224523c9-a087-4bef-a75b-617f77b23cb4": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "224523c9-a087-4bef-a75b-617f77b23cb4",
      "parent": "36565ae1-cd9c-4c07-95b2-8732b7664e4b",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "430086a1-6664-43c9-bcdb-58b821ef4331": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "430086a1-6664-43c9-bcdb-58b821ef4331",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [
        "e3063b95-b35c-4331-a7df-89c961598188"
      ],
      "position": [
        -40.96033477783203,
        -0.1259450912475586,
        -26.096173022514108
      ],
      "rotation": [
        0,
        31.612833901621407,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197285,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "e3063b95-b35c-4331-a7df-89c961598188": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "e3063b95-b35c-4331-a7df-89c961598188",
      "parent": "430086a1-6664-43c9-bcdb-58b821ef4331",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "005c6246-ec2c-421a-98b3-2bf0883bb839": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "005c6246-ec2c-421a-98b3-2bf0883bb839",
      "parent": "6bb3e0d9-6575-4090-aca4-9d4838fb96c9",
      "children": [],
      "position": [
        6.618989115274262,
        1.0890490216273179,
        1.1073117936180097
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            0.28,
            4,
            0.2
          ],
          "radius": 3.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "90d136f2-22f0-4943-90bc-4056ceca0921": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "90d136f2-22f0-4943-90bc-4056ceca0921",
      "parent": "6bb3e0d9-6575-4090-aca4-9d4838fb96c9",
      "children": [],
      "position": [
        6.618989568740176,
        1.0890490216273179,
        -1.0014830982699792
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            0.28,
            4,
            0.2
          ],
          "radius": 3.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "b5949fc0-6b75-48f7-a419-2368ef7d5a0d": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "b5949fc0-6b75-48f7-a419-2368ef7d5a0d",
      "parent": "6bb3e0d9-6575-4090-aca4-9d4838fb96c9",
      "children": [],
      "position": [
        6.618989568740176,
        1.0890490216273179,
        3.1824400314957515
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            0.28,
            4,
            0.2
          ],
          "radius": 3.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "e3a30cb7-e6a6-4e46-a027-410c16b352df": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "e3a30cb7-e6a6-4e46-a027-410c16b352df",
      "parent": "6bb3e0d9-6575-4090-aca4-9d4838fb96c9",
      "children": [],
      "position": [
        5.055061023842086,
        2.428026224889125,
        1.244729256028677
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            5,
            0.2,
            5
          ],
          "radius": 3.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "6944a160-70c6-4e36-a64c-30e5413ac354": {
      "name": "building_base_block7",
      "tags": [],
      "enabled": true,
      "resource_id": "6944a160-70c6-4e36-a64c-30e5413ac354",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [
        "b088bc32-fd1a-40e9-b447-bed9aec46f5d",
        "5a422038-12be-442f-b42d-a1f40a59c837",
        "89a4f784-b1ac-4904-8e28-35b3e561bf99",
        "df0c5c35-4d3b-4951-85a0-d01559c53da3",
        "59c6cd3d-4d68-4f54-ac26-8d775e8d01a5",
        "02d73124-097f-4122-914f-3ced72b7a9e3"
      ],
      "position": [
        -27.04996133035051,
        -0.19701480865478516,
        -42.928062438964844
      ],
      "rotation": [
        0,
        -77.06005978887501,
        0
      ],
      "scale": [
        2.6445208631980615,
        2.6445208631980615,
        2.6445208631980615
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 29699871,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100009
        }
      }
    },
    "b088bc32-fd1a-40e9-b447-bed9aec46f5d": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "b088bc32-fd1a-40e9-b447-bed9aec46f5d",
      "parent": "6944a160-70c6-4e36-a64c-30e5413ac354",
      "children": [],
      "position": [
        1.1852543618747404,
        1.1663351649280855,
        0.9835100550188756
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            7.5,
            5,
            8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "5a422038-12be-442f-b42d-a1f40a59c837": {
      "name": "awning_2_hue1",
      "tags": [],
      "enabled": true,
      "resource_id": "5a422038-12be-442f-b42d-a1f40a59c837",
      "parent": "6944a160-70c6-4e36-a64c-30e5413ac354",
      "children": [],
      "position": [
        4.06938580791223,
        5.312000439516851e-8,
        1.1022024905039416
      ],
      "rotation": [
        180,
        90,
        180
      ],
      "scale": [
        1,
        1,
        1.5705831544250461
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 29700053,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100010
        }
      }
    },
    "89a4f784-b1ac-4904-8e28-35b3e561bf99": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "89a4f784-b1ac-4904-8e28-35b3e561bf99",
      "parent": "6944a160-70c6-4e36-a64c-30e5413ac354",
      "children": [],
      "position": [
        6.618989115274262,
        1.0890490216273179,
        1.1073117936180097
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            0.28,
            4,
            0.2
          ],
          "radius": 3.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "df0c5c35-4d3b-4951-85a0-d01559c53da3": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "df0c5c35-4d3b-4951-85a0-d01559c53da3",
      "parent": "6944a160-70c6-4e36-a64c-30e5413ac354",
      "children": [],
      "position": [
        6.618989568740176,
        1.0890490216273179,
        -1.0014830982699792
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            0.28,
            4,
            0.2
          ],
          "radius": 3.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "59c6cd3d-4d68-4f54-ac26-8d775e8d01a5": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "59c6cd3d-4d68-4f54-ac26-8d775e8d01a5",
      "parent": "6944a160-70c6-4e36-a64c-30e5413ac354",
      "children": [],
      "position": [
        6.618989568740176,
        1.0890490216273179,
        3.1824400314957515
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            0.28,
            4,
            0.2
          ],
          "radius": 3.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "02d73124-097f-4122-914f-3ced72b7a9e3": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "02d73124-097f-4122-914f-3ced72b7a9e3",
      "parent": "6944a160-70c6-4e36-a64c-30e5413ac354",
      "children": [],
      "position": [
        5.055061023842086,
        2.428026224889125,
        1.244729256028677
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            5,
            0.2,
            5
          ],
          "radius": 3.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "6eba1617-c02d-44e7-bba7-ede21b07308a": {
      "name": "building_base_block7",
      "tags": [],
      "enabled": true,
      "resource_id": "6eba1617-c02d-44e7-bba7-ede21b07308a",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [
        "5b82440c-accf-4147-a765-b75fcc187804",
        "91320872-a809-4802-bd4f-cf1a15c523d6",
        "84dd4d4e-e7c6-431a-ac05-bdf83d363290",
        "a99c0331-e408-4f1a-95e4-0b06ddaa555d",
        "490fe72c-796d-4ee2-9406-a5406d9424bd",
        "5c6f2bce-d758-42a7-8676-a1f464252658"
      ],
      "position": [
        -4.392830102308779,
        -0.19701480865478516,
        -40.42533068839855
      ],
      "rotation": [
        0,
        -89.0060458524072,
        0
      ],
      "scale": [
        2.6445208631980615,
        2.6445208631980615,
        2.6445208631980615
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 29699871,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100009
        }
      }
    },
    "5b82440c-accf-4147-a765-b75fcc187804": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "5b82440c-accf-4147-a765-b75fcc187804",
      "parent": "6eba1617-c02d-44e7-bba7-ede21b07308a",
      "children": [],
      "position": [
        1.1852543618747404,
        1.1663351649280855,
        0.9835100550188756
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            7.5,
            5,
            8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "91320872-a809-4802-bd4f-cf1a15c523d6": {
      "name": "awning_2_hue1",
      "tags": [],
      "enabled": true,
      "resource_id": "91320872-a809-4802-bd4f-cf1a15c523d6",
      "parent": "6eba1617-c02d-44e7-bba7-ede21b07308a",
      "children": [],
      "position": [
        4.06938580791223,
        5.312000439516851e-8,
        1.1022024905039416
      ],
      "rotation": [
        180,
        90,
        180
      ],
      "scale": [
        1,
        1,
        1.5705831544250461
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 29700053,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100010
        }
      }
    },
    "84dd4d4e-e7c6-431a-ac05-bdf83d363290": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "84dd4d4e-e7c6-431a-ac05-bdf83d363290",
      "parent": "6eba1617-c02d-44e7-bba7-ede21b07308a",
      "children": [],
      "position": [
        6.618989115274262,
        1.0890490216273179,
        1.1073117936180097
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            0.28,
            4,
            0.2
          ],
          "radius": 3.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "a99c0331-e408-4f1a-95e4-0b06ddaa555d": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "a99c0331-e408-4f1a-95e4-0b06ddaa555d",
      "parent": "6eba1617-c02d-44e7-bba7-ede21b07308a",
      "children": [],
      "position": [
        6.618989568740176,
        1.0890490216273179,
        -1.0014830982699792
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            0.28,
            4,
            0.2
          ],
          "radius": 3.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "490fe72c-796d-4ee2-9406-a5406d9424bd": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "490fe72c-796d-4ee2-9406-a5406d9424bd",
      "parent": "6eba1617-c02d-44e7-bba7-ede21b07308a",
      "children": [],
      "position": [
        6.618989568740176,
        1.0890490216273179,
        3.1824400314957515
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            0.28,
            4,
            0.2
          ],
          "radius": 3.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "5c6f2bce-d758-42a7-8676-a1f464252658": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "5c6f2bce-d758-42a7-8676-a1f464252658",
      "parent": "6eba1617-c02d-44e7-bba7-ede21b07308a",
      "children": [],
      "position": [
        5.055061023842086,
        2.428026224889125,
        1.244729256028677
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            5,
            0.2,
            5
          ],
          "radius": 3.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "df328856-ab85-446c-883c-aa867fa3ed9a": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "df328856-ab85-446c-883c-aa867fa3ed9a",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "3e70513d-da77-4928-a3b0-1a2b7a8af082"
      ],
      "position": [
        23.92009980649229,
        10.143437385559082,
        -120.49252319335938
      ],
      "rotation": [
        180,
        90,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "3e70513d-da77-4928-a3b0-1a2b7a8af082": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "3e70513d-da77-4928-a3b0-1a2b7a8af082",
      "parent": "df328856-ab85-446c-883c-aa867fa3ed9a",
      "children": [],
      "position": [
        5.662551139096195e-8,
        2.6054763805246406,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "ee30513d-2f16-4884-b02e-709c124b5b5b": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "ee30513d-2f16-4884-b02e-709c124b5b5b",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "7cba106c-501a-484a-a6dc-1895a23ce979"
      ],
      "position": [
        20.76102064351562,
        10.143437385559082,
        -130.92339185702335
      ],
      "rotation": [
        180,
        60.316177404060475,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "7cba106c-501a-484a-a6dc-1895a23ce979": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "7cba106c-501a-484a-a6dc-1895a23ce979",
      "parent": "ee30513d-2f16-4884-b02e-709c124b5b5b",
      "children": [],
      "position": [
        5.662551139096195e-8,
        2.8979377242537687,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "1d19ecb0-7353-4ce1-9a7c-77b4d4ccda25": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "1d19ecb0-7353-4ce1-9a7c-77b4d4ccda25",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "b99f44ff-783f-4d86-8694-276d99cadfbf"
      ],
      "position": [
        12.984794828050342,
        10.143437385559082,
        -139.4091561318331
      ],
      "rotation": [
        180,
        36.04238116566158,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "b99f44ff-783f-4d86-8694-276d99cadfbf": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "b99f44ff-783f-4d86-8694-276d99cadfbf",
      "parent": "1d19ecb0-7353-4ce1-9a7c-77b4d4ccda25",
      "children": [],
      "position": [
        5.662551139096195e-8,
        2.630512728210494,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "9f252ab7-173b-4152-b3a9-957cf7bf9eeb": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "9f252ab7-173b-4152-b3a9-957cf7bf9eeb",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "80f29a2d-6650-4127-b4bc-8dbcf9fe8220"
      ],
      "position": [
        5.042745255712467,
        10.143437385559082,
        -147.71646247099815
      ],
      "rotation": [
        180,
        56.412711530844284,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "80f29a2d-6650-4127-b4bc-8dbcf9fe8220": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "80f29a2d-6650-4127-b4bc-8dbcf9fe8220",
      "parent": "9f252ab7-173b-4152-b3a9-957cf7bf9eeb",
      "children": [],
      "position": [
        1.1253873355111916,
        2.8979377242537687,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            10,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "443150fa-4e5e-4a29-8a08-49c90f74592a": {
      "name": "building_base_block3",
      "tags": [],
      "enabled": true,
      "resource_id": "443150fa-4e5e-4a29-8a08-49c90f74592a",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [],
      "position": [
        5.6841204848388065,
        0,
        -43.29231592271945
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.000925918548337,
        3.000925918548337,
        3.000925918548337
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30883287,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100009
        }
      }
    },
    "ad4b2662-7f31-4b6b-a6bb-45a088fa669e": {
      "name": "scaffolding_1x2_wall_mounted",
      "tags": [],
      "enabled": true,
      "resource_id": "ad4b2662-7f31-4b6b-a6bb-45a088fa669e",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [],
      "position": [
        5.645262602785858,
        17.008866219212315,
        -35.61661822070229
      ],
      "rotation": [
        7.84342708142863e-15,
        0,
        -1.0521725561199325e-14
      ],
      "scale": [
        4.102322486480364,
        4.102322486480364,
        4.102322486480364
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30883305,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "e161e018-b756-4a9a-8c8b-be5840e8d32b": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "e161e018-b756-4a9a-8c8b-be5840e8d32b",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "05e230c1-542e-44ff-b411-3f8e07cb398f"
      ],
      "position": [
        -53.96096840504678,
        10.143437444051669,
        -136.30499094912227
      ],
      "rotation": [
        179.99999999999997,
        -70.52836949162727,
        -180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "05e230c1-542e-44ff-b411-3f8e07cb398f": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "05e230c1-542e-44ff-b411-3f8e07cb398f",
      "parent": "e161e018-b756-4a9a-8c8b-be5840e8d32b",
      "children": [],
      "position": [
        5.662551139096195e-8,
        3.314691450779586,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "dc7d92df-4590-4a1c-9c54-4297db17ce24": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "dc7d92df-4590-4a1c-9c54-4297db17ce24",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "dac50200-4623-4b4c-9fd1-7db8e04a04c5"
      ],
      "position": [
        -48.4701845965798,
        10.143437444051669,
        -147.18280688150261
      ],
      "rotation": [
        180,
        -56.26013641534871,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "dac50200-4623-4b4c-9fd1-7db8e04a04c5": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "dac50200-4623-4b4c-9fd1-7db8e04a04c5",
      "parent": "dc7d92df-4590-4a1c-9c54-4297db17ce24",
      "children": [],
      "position": [
        5.662551139096195e-8,
        3.314691450779586,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "9a720aa6-52fe-4727-b03b-c039112afac6": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "9a720aa6-52fe-4727-b03b-c039112afac6",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "075fd519-6e7f-4be8-9afe-4788e204439f"
      ],
      "position": [
        -39.7704859961943,
        10.143437444051667,
        -155.36511658588154
      ],
      "rotation": [
        180,
        -30.312756358485412,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "075fd519-6e7f-4be8-9afe-4788e204439f": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "075fd519-6e7f-4be8-9afe-4788e204439f",
      "parent": "9a720aa6-52fe-4727-b03b-c039112afac6",
      "children": [],
      "position": [
        5.662551139096195e-8,
        3.314691450779586,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.3,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "f8394b53-cd59-4e03-a92e-883ca92b94d7": {
      "name": "building_base_block3",
      "tags": [],
      "enabled": true,
      "resource_id": "f8394b53-cd59-4e03-a92e-883ca92b94d7",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [
        "89e0aed7-da0c-48ca-80c0-9530c2c318c9"
      ],
      "position": [
        -18.26522548167488,
        -6.1286302866617035,
        -49.81748207016763
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.000925918548337,
        3.000925918548337,
        3.000925918548337
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30883287,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100009
        }
      }
    },
    "acbfe81f-b51f-4aca-bcf5-030e25a1bdb6": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "acbfe81f-b51f-4aca-bcf5-030e25a1bdb6",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -36.505588204816235,
        14.970879896079097,
        -160.66981929173485
      ],
      "rotation": [
        0,
        4.669001478714261,
        0
      ],
      "scale": [
        2.6616259368859194,
        3.1305022865230265,
        2.6616259368859194
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "60a32e32-5d88-4453-8e66-b085912c47cb": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "60a32e32-5d88-4453-8e66-b085912c47cb",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -60.13998170355369,
        13.24172569891869,
        -134.81099975465418
      ],
      "rotation": [
        180,
        -87.86615717182856,
        180
      ],
      "scale": [
        2.6616259368859194,
        3.1305022865230265,
        2.6616259368859194
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "89e0aed7-da0c-48ca-80c0-9530c2c318c9": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "89e0aed7-da0c-48ca-80c0-9530c2c318c9",
      "parent": "f8394b53-cd59-4e03-a92e-883ca92b94d7",
      "children": [],
      "position": [
        0.0000015932271821839095,
        4.195076800298466,
        1.1998399073899861
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            30,
            10,
            2.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "2de6e3e4-987b-43a1-b6aa-64babd81f36a": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "2de6e3e4-987b-43a1-b6aa-64babd81f36a",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [
        "3f44680e-7ce8-4273-bd7a-5e91780cc6e4"
      ],
      "position": [
        23.08706591409736,
        -0.1259450912475586,
        5.4781207210558
      ],
      "rotation": [
        0,
        -5.584952442418447,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197280,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "3f44680e-7ce8-4273-bd7a-5e91780cc6e4": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "3f44680e-7ce8-4273-bd7a-5e91780cc6e4",
      "parent": "2de6e3e4-987b-43a1-b6aa-64babd81f36a",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "0998955e-bab1-42b0-99ed-128800babf3a": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "0998955e-bab1-42b0-99ed-128800babf3a",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [
        "4489a858-0214-4f02-81d6-139d3a58d616"
      ],
      "position": [
        8.511440511134047,
        -0.1259450912475586,
        -21.069455990660174
      ],
      "rotation": [
        0,
        -42.494334606348275,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197280,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "4489a858-0214-4f02-81d6-139d3a58d616": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "4489a858-0214-4f02-81d6-139d3a58d616",
      "parent": "0998955e-bab1-42b0-99ed-128800babf3a",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "64c05253-b842-48ab-9c4b-6d37b05f5931": {
      "name": "blue",
      "tags": [
        "SpawnPoint"
      ],
      "enabled": true,
      "resource_id": "64c05253-b842-48ab-9c4b-6d37b05f5931",
      "parent": "317a1d13-b11c-4f26-bede-e4324b7cf98a",
      "children": [],
      "position": [
        15.091605186462402,
        12.898055076599121,
        -122.68681511466812
      ],
      "rotation": [
        0,
        89.00561208665917,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "70a980d1-928d-4c57-b671-a79edb19247b": {
      "name": "red",
      "tags": [
        "SpawnPoint"
      ],
      "enabled": true,
      "resource_id": "70a980d1-928d-4c57-b671-a79edb19247b",
      "parent": "317a1d13-b11c-4f26-bede-e4324b7cf98a",
      "children": [],
      "position": [
        -31.554325103759766,
        12.898055076599121,
        -125.45070235088299
      ],
      "rotation": [
        0,
        89.00561208665917,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "6bd26262-8743-44ea-97a8-e9985bc24a85": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "6bd26262-8743-44ea-97a8-e9985bc24a85",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "98729322-c2a9-49dc-bf3b-b70492ae6a0b"
      ],
      "position": [
        8.870216369628906,
        10.192291259765625,
        -93.81512084651185
      ],
      "rotation": [
        0,
        -28.789413447115834,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 29700044,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "98729322-c2a9-49dc-bf3b-b70492ae6a0b": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "98729322-c2a9-49dc-bf3b-b70492ae6a0b",
      "parent": "6bd26262-8743-44ea-97a8-e9985bc24a85",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "7f280e84-1638-40a8-a807-34659d269c5e": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "7f280e84-1638-40a8-a807-34659d269c5e",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "412ab1a3-5a83-40a8-acb6-f5814bd555ec"
      ],
      "position": [
        -44.609330867425065,
        10.192291259765625,
        -112.4656982421875
      ],
      "rotation": [
        0,
        -28.789413447115834,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 29700044,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "412ab1a3-5a83-40a8-acb6-f5814bd555ec": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "412ab1a3-5a83-40a8-acb6-f5814bd555ec",
      "parent": "7f280e84-1638-40a8-a807-34659d269c5e",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "2829f820-8dd7-4ce5-a3ae-666af2bf1a55": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "2829f820-8dd7-4ce5-a3ae-666af2bf1a55",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "2206afcd-7345-4000-97c6-4edb869a5c58"
      ],
      "position": [
        -9.766125679016113,
        10.192291259765625,
        -124.68844821715327
      ],
      "rotation": [
        0,
        -28.789413447115834,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 29700044,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "2206afcd-7345-4000-97c6-4edb869a5c58": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "2206afcd-7345-4000-97c6-4edb869a5c58",
      "parent": "2829f820-8dd7-4ce5-a3ae-666af2bf1a55",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "e26f434e-2ac0-4709-b2f6-707d28dade71": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "e26f434e-2ac0-4709-b2f6-707d28dade71",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "9b49d1ae-a36c-46eb-abee-6896d5b59eaa"
      ],
      "position": [
        -17.061812288357707,
        10.192291259765625,
        -143.66677856445312
      ],
      "rotation": [
        0,
        -28.789413447115834,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 29700044,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "9b49d1ae-a36c-46eb-abee-6896d5b59eaa": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "9b49d1ae-a36c-46eb-abee-6896d5b59eaa",
      "parent": "e26f434e-2ac0-4709-b2f6-707d28dade71",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "c997ea5f-51e7-4b79-bb00-c5b93103b7bb": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "c997ea5f-51e7-4b79-bb00-c5b93103b7bb",
      "parent": "a6b4e0d5-8149-4668-824b-bab2a387ef5f",
      "children": [
        "432dff5b-b1e3-4e3f-b56c-c74eb597e61b"
      ],
      "position": [
        -40.06455212530418,
        -0.1259450912475586,
        15.106254577636719
      ],
      "rotation": [
        0,
        31.612833901621407,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197285,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "432dff5b-b1e3-4e3f-b56c-c74eb597e61b": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "432dff5b-b1e3-4e3f-b56c-c74eb597e61b",
      "parent": "c997ea5f-51e7-4b79-bb00-c5b93103b7bb",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "0cb35937-b91b-4d24-b55c-8a4ee74fc2bd": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "0cb35937-b91b-4d24-b55c-8a4ee74fc2bd",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        33.10683059692383,
        16.518426304375684,
        -86.77015686035156
      ],
      "rotation": [
        180,
        72.79488458179841,
        180
      ],
      "scale": [
        2.6616259368859194,
        3.1305022865230265,
        2.6616259368859194
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "468a48f8-9ce1-4813-b919-b2b7bddae9cc": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "468a48f8-9ce1-4813-b919-b2b7bddae9cc",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        27.598803670992197,
        16.5184268951416,
        -116.4878158569336
      ],
      "rotation": [
        180,
        18.423035853111866,
        180
      ],
      "scale": [
        2.1068848253585895,
        2.4780370794487143,
        2.1068848253585895
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100005
        }
      }
    },
    "07cf7750-86ee-4886-a513-6f064142f725": {
      "name": "Grass",
      "tags": [],
      "enabled": true,
      "resource_id": "07cf7750-86ee-4886-a513-6f064142f725",
      "parent": "a84eb64b-ae5c-49f9-bb7c-a0746aae0286",
      "children": [
        "93ca50e9-e89b-4d7e-9f99-884389c0809d",
        "9a3a48f0-10c0-4f46-b020-56dfffea6b11",
        "80c0977f-02cc-4f30-b5a9-3044a9cb59e3",
        "410f49c3-20c8-4185-8de9-7f60eccd8c46",
        "e6dfbbce-a48b-4f6a-8dba-891bdeba98b7",
        "f8e7ff7d-dbda-40be-a85e-948215c5ebb4",
        "68b621f4-36b9-46f4-ac89-f02693b214ae",
        "8f99253f-9ee0-4bd1-91a7-cf3e67ff6d8e",
        "b2fc218b-4695-425f-b7ef-394b8493765d",
        "c5edcb5c-929a-4488-9e03-e740fccaa65f",
        "d1fb4d58-a893-431e-b7cc-696eff59e186",
        "6bb4d71e-7665-4704-b58e-d848b40e9274",
        "a5d9db5a-3950-4cfd-aac4-c408c7928907"
      ],
      "position": [
        0,
        0,
        0
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "93ca50e9-e89b-4d7e-9f99-884389c0809d": {
      "name": "Grass",
      "tags": [],
      "enabled": true,
      "resource_id": "93ca50e9-e89b-4d7e-9f99-884389c0809d",
      "parent": "07cf7750-86ee-4886-a513-6f064142f725",
      "children": [],
      "position": [
        -6.46546592931878,
        0,
        6.313730716705322
      ],
      "rotation": [
        0,
        -19.255412024905677,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31441653,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100011
        }
      }
    },
    "f8e7ff7d-dbda-40be-a85e-948215c5ebb4": {
      "name": "Grass",
      "tags": [],
      "enabled": true,
      "resource_id": "f8e7ff7d-dbda-40be-a85e-948215c5ebb4",
      "parent": "07cf7750-86ee-4886-a513-6f064142f725",
      "children": [],
      "position": [
        31.949500800847495,
        0,
        -6.918980121612549
      ],
      "rotation": [
        0,
        12.144975388877283,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31441653,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100011
        }
      }
    },
    "68b621f4-36b9-46f4-ac89-f02693b214ae": {
      "name": "Grass",
      "tags": [],
      "enabled": true,
      "resource_id": "68b621f4-36b9-46f4-ac89-f02693b214ae",
      "parent": "07cf7750-86ee-4886-a513-6f064142f725",
      "children": [],
      "position": [
        -21.70540848984642,
        0,
        -14.893670082092285
      ],
      "rotation": [
        0,
        56.86232982761113,
        0
      ],
      "scale": [
        1.0700910152570793,
        1.0700910152570793,
        1.0700910152570793
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31441653,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100011
        }
      }
    },
    "8f99253f-9ee0-4bd1-91a7-cf3e67ff6d8e": {
      "name": "Grass",
      "tags": [],
      "enabled": true,
      "resource_id": "8f99253f-9ee0-4bd1-91a7-cf3e67ff6d8e",
      "parent": "07cf7750-86ee-4886-a513-6f064142f725",
      "children": [],
      "position": [
        7.522851467132568,
        0,
        -33.15599769095661
      ],
      "rotation": [
        0,
        56.86232982761113,
        0
      ],
      "scale": [
        1.0700910152570793,
        1.0700910152570793,
        1.0700910152570793
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31441653,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100011
        }
      }
    },
    "b2fc218b-4695-425f-b7ef-394b8493765d": {
      "name": "Grass",
      "tags": [],
      "enabled": true,
      "resource_id": "b2fc218b-4695-425f-b7ef-394b8493765d",
      "parent": "07cf7750-86ee-4886-a513-6f064142f725",
      "children": [],
      "position": [
        -82.78575897216797,
        0,
        -47.83586833053935
      ],
      "rotation": [
        180,
        55.091889289227915,
        180
      ],
      "scale": [
        1.356138566464519,
        1.356138566464519,
        1.356138566464519
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31441653,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100011
        }
      }
    },
    "d1fb4d58-a893-431e-b7cc-696eff59e186": {
      "name": "Grass",
      "tags": [],
      "enabled": true,
      "resource_id": "d1fb4d58-a893-431e-b7cc-696eff59e186",
      "parent": "07cf7750-86ee-4886-a513-6f064142f725",
      "children": [],
      "position": [
        -40.14729309082031,
        10.104387283325195,
        -147.5304292300316
      ],
      "rotation": [
        180,
        55.091889289227915,
        180
      ],
      "scale": [
        1.356138566464519,
        1.356138566464519,
        1.356138566464519
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31441653,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100011
        }
      }
    },
    "6bb4d71e-7665-4704-b58e-d848b40e9274": {
      "name": "Grass",
      "tags": [],
      "enabled": true,
      "resource_id": "6bb4d71e-7665-4704-b58e-d848b40e9274",
      "parent": "07cf7750-86ee-4886-a513-6f064142f725",
      "children": [],
      "position": [
        -2.4235196113586426,
        10.104387283325195,
        -121.3330844688958
      ],
      "rotation": [
        180,
        55.091889289227915,
        180
      ],
      "scale": [
        0.8865139786822094,
        0.8865139786822094,
        0.8865139786822094
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31441653,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100011
        }
      }
    },
    "9a3a48f0-10c0-4f46-b020-56dfffea6b11": {
      "name": "Grass",
      "tags": [],
      "enabled": true,
      "resource_id": "9a3a48f0-10c0-4f46-b020-56dfffea6b11",
      "parent": "07cf7750-86ee-4886-a513-6f064142f725",
      "children": [],
      "position": [
        17.178698776860653,
        0,
        29.752450942993164
      ],
      "rotation": [
        0,
        51.874141628465665,
        0
      ],
      "scale": [
        0.7080669997335788,
        0.7080669997335788,
        0.7080669997335788
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31441653,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100011
        }
      }
    },
    "410f49c3-20c8-4185-8de9-7f60eccd8c46": {
      "name": "Grass",
      "tags": [],
      "enabled": true,
      "resource_id": "410f49c3-20c8-4185-8de9-7f60eccd8c46",
      "parent": "07cf7750-86ee-4886-a513-6f064142f725",
      "children": [],
      "position": [
        69.82114221899715,
        2.922564336948278e-16,
        18.462153693043696
      ],
      "rotation": [
        180,
        64.29019035712062,
        180
      ],
      "scale": [
        0.7080669997335788,
        0.7080669997335788,
        0.7080669997335788
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31441653,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100011
        }
      }
    },
    "e6dfbbce-a48b-4f6a-8dba-891bdeba98b7": {
      "name": "Grass",
      "tags": [],
      "enabled": true,
      "resource_id": "e6dfbbce-a48b-4f6a-8dba-891bdeba98b7",
      "parent": "07cf7750-86ee-4886-a513-6f064142f725",
      "children": [],
      "position": [
        46.68897480356268,
        1.2588908444162452e-15,
        5.54611910650572
      ],
      "rotation": [
        180,
        -59.82004013214614,
        -180
      ],
      "scale": [
        0.7080669997335788,
        0.7080669997335788,
        0.7080669997335788
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31441653,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100011
        }
      }
    },
    "e3dc16ac-1132-4c10-94ab-9dc1a0e5db70": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "e3dc16ac-1132-4c10-94ab-9dc1a0e5db70",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        30.525083853793983,
        18.414965006870634,
        -32.19897835332725
      ],
      "rotation": [
        -163.3027627664536,
        35.18617162197889,
        -156.86555521230073
      ],
      "scale": [
        2.6967219098784394,
        2.6967219098784394,
        2.6967219098784394
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "91752b3a-bef1-4d41-ae86-c385046c07df": {
      "name": "wall_pannel_01_shade_3",
      "tags": [],
      "enabled": true,
      "resource_id": "91752b3a-bef1-4d41-ae86-c385046c07df",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        42.04803992752938,
        9.5603609085083,
        15.805233001708984
      ],
      "rotation": [
        0,
        -90,
        0
      ],
      "scale": [
        6.581725378563207,
        7.244566294022107,
        10.775200642972559
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30017386,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100004
        }
      }
    },
    "2250204c-8b4a-49ad-94cc-d12f99c414b8": {
      "name": "Water",
      "tags": [
        "Rigidbody",
        "Water"
      ],
      "enabled": true,
      "resource_id": "2250204c-8b4a-49ad-94cc-d12f99c414b8",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -6.2776336669921875,
        8.081947256938435,
        40.774356842041016
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        25.59309531456463,
        25.59309531456463,
        25.59309531456463
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "plane",
          "asset": null,
          "materialAsset": 31694990,
          "castShadows": false,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        },
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            10,
            0.5,
            13
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "ebd1da03-0d1d-4d0d-bd59-9890a95e12c5": {
      "name": "wall_mid_double",
      "tags": [],
      "enabled": true,
      "resource_id": "ebd1da03-0d1d-4d0d-bd59-9890a95e12c5",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -9.587812514909977,
        0.020066730678081512,
        25.560766220092773
      ],
      "rotation": [
        180,
        0,
        180
      ],
      "scale": [
        3.1388328257127625,
        2.4306359171978094,
        2.2894859943353087
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30534359,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "c9f42087-a05e-408f-9527-502332f93260": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "c9f42087-a05e-408f-9527-502332f93260",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "2158f5fa-6750-4a91-b95e-39079aa3f8a0"
      ],
      "position": [
        -13.336687088012695,
        9.722262472894025,
        15.069283485412598
      ],
      "rotation": [
        0,
        8.351440703722751,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197280,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "2158f5fa-6750-4a91-b95e-39079aa3f8a0": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "2158f5fa-6750-4a91-b95e-39079aa3f8a0",
      "parent": "c9f42087-a05e-408f-9527-502332f93260",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "aa369f96-fdbc-4b2b-b8e5-515045ee4463": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "aa369f96-fdbc-4b2b-b8e5-515045ee4463",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "11d961e5-31e5-44ea-90d3-71d39d62e2f7"
      ],
      "position": [
        -10.150167971490028,
        9.722262382507324,
        19.92534828186035
      ],
      "rotation": [
        0,
        43.34182557028059,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197280,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "11d961e5-31e5-44ea-90d3-71d39d62e2f7": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "11d961e5-31e5-44ea-90d3-71d39d62e2f7",
      "parent": "aa369f96-fdbc-4b2b-b8e5-515045ee4463",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "b630031c-f13d-47b7-800c-81b4ad143df3": {
      "name": "box_large_2",
      "tags": [],
      "enabled": true,
      "resource_id": "b630031c-f13d-47b7-800c-81b4ad143df3",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "d197565a-0cb6-4f87-93ce-7a9007e8fac7"
      ],
      "position": [
        -12.997870327319488,
        9.722262382507324,
        23.92767906188965
      ],
      "rotation": [
        0,
        43.34182557028059,
        0
      ],
      "scale": [
        4,
        4,
        4
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31197280,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "d197565a-0cb6-4f87-93ce-7a9007e8fac7": {
      "name": "Box",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "d197565a-0cb6-4f87-93ce-7a9007e8fac7",
      "parent": "b630031c-f13d-47b7-800c-81b4ad143df3",
      "children": [],
      "position": [
        5.662551139096195e-8,
        0.5,
        7.972903404152021e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            2,
            2,
            2
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 1,
          "restitution": 0.5
        }
      }
    },
    "77d45c39-061c-4739-832d-a5a5e6818d76": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "77d45c39-061c-4739-832d-a5a5e6818d76",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -13.937994003295898,
        9.46185203722953,
        19.324851989746094
      ],
      "rotation": [
        180,
        60.083467956548944,
        180
      ],
      "scale": [
        2.3802338609426457,
        2.3802338609426457,
        2.3802338609426457
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "7ebea48a-0275-4c9d-8807-98d8728ee864": {
      "name": "Dangerous",
      "tags": [],
      "enabled": true,
      "resource_id": "7ebea48a-0275-4c9d-8807-98d8728ee864",
      "parent": "a84eb64b-ae5c-49f9-bb7c-a0746aae0286",
      "children": [
        "d05d3447-f7ec-4a29-a560-73da3d7d55e4",
        "b2d09f4d-e2f4-40a6-8f5a-d4cce370535e",
        "08aaf7ab-2c3c-4fe9-ba8e-9569c727efb9",
        "1bd67066-ee3f-4c13-ae74-0fccdc894678"
      ],
      "position": [
        0,
        0,
        0
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "db8cda9a-b91e-4aaa-b9fe-1d175d656fec": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Wood"
      ],
      "enabled": true,
      "resource_id": "db8cda9a-b91e-4aaa-b9fe-1d175d656fec",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -45.24511671777838,
        12.816400554846325,
        8.151874692294024
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "cylinder",
          "halfExtents": [
            2,
            7,
            2
          ],
          "radius": 1.5,
          "axis": 1,
          "height": 10,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "355f02b8-9584-4203-90bd-32e8f4c5bba3": {
      "name": "palm_tree_4",
      "tags": [],
      "enabled": true,
      "resource_id": "355f02b8-9584-4203-90bd-32e8f4c5bba3",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [],
      "position": [
        -85.8313980102539,
        3.7009325910932667,
        13.506117820739746
      ],
      "rotation": [
        0,
        32.221826149602094,
        0
      ],
      "scale": [
        4.589281387917414,
        5.397736653852276,
        4.589281387917414
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30536187,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100000
        }
      }
    },
    "c5edcb5c-929a-4488-9e03-e740fccaa65f": {
      "name": "Grass",
      "tags": [],
      "enabled": true,
      "resource_id": "c5edcb5c-929a-4488-9e03-e740fccaa65f",
      "parent": "07cf7750-86ee-4886-a513-6f064142f725",
      "children": [],
      "position": [
        -81.42156982421875,
        0,
        -3.6251369968697906
      ],
      "rotation": [
        180,
        -12.421743897666046,
        180
      ],
      "scale": [
        1.356138566464519,
        1.356138566464519,
        1.356138566464519
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31441653,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100011
        }
      }
    },
    "a5d9db5a-3950-4cfd-aac4-c408c7928907": {
      "name": "Grass",
      "tags": [],
      "enabled": true,
      "resource_id": "a5d9db5a-3950-4cfd-aac4-c408c7928907",
      "parent": "07cf7750-86ee-4886-a513-6f064142f725",
      "children": [],
      "position": [
        18.54201018964692,
        10.104387283325195,
        -121.33308410644531
      ],
      "rotation": [
        180,
        55.091889289227915,
        180
      ],
      "scale": [
        0.8865139786822094,
        0.8865139786822094,
        0.8865139786822094
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31441653,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100011
        }
      }
    },
    "e4705144-412c-410a-b1f4-b93d3996f1e6": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick",
        "Grapple"
      ],
      "enabled": true,
      "resource_id": "e4705144-412c-410a-b1f4-b93d3996f1e6",
      "parent": "d1011fa8-b4e4-4675-98f1-63884dd849a6",
      "children": [],
      "position": [
        0,
        5.762123456614736,
        4.809176204424314e-16
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.5,
            5,
            10.8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "198e10d0-6868-41e0-83bc-833cefadf396": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick"
      ],
      "enabled": true,
      "resource_id": "198e10d0-6868-41e0-83bc-833cefadf396",
      "parent": "d1011fa8-b4e4-4675-98f1-63884dd849a6",
      "children": [],
      "position": [
        2.0731594130822852,
        7.798532960880834,
        -0.666832976247349
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            0.5,
            4.2,
            7
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "359ac1b1-117b-436f-ba97-467a207839b9": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "359ac1b1-117b-436f-ba97-467a207839b9",
      "parent": "e84fdf83-700a-4ae9-94b7-b29a07a3759a",
      "children": [],
      "position": [
        -3.422133749729495,
        0.2605459688502094,
        -0.11141232384170685
      ],
      "rotation": [
        44.90131493372405,
        -1.1273852673265173e-15,
        4.635713606664996e-15
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            20,
            1.18,
            3.65
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "d05d3447-f7ec-4a29-a560-73da3d7d55e4": {
      "name": "Kill",
      "tags": [
        "Kill"
      ],
      "enabled": true,
      "resource_id": "d05d3447-f7ec-4a29-a560-73da3d7d55e4",
      "parent": "7ebea48a-0275-4c9d-8807-98d8728ee864",
      "children": [],
      "position": [
        -7.0123443603515625,
        0.23151956498622894,
        81.55174152894527
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            100,
            4,
            40
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "08aaf7ab-2c3c-4fe9-ba8e-9569c727efb9": {
      "name": "Kill",
      "tags": [
        "Kill"
      ],
      "enabled": true,
      "resource_id": "08aaf7ab-2c3c-4fe9-ba8e-9569c727efb9",
      "parent": "7ebea48a-0275-4c9d-8807-98d8728ee864",
      "children": [],
      "position": [
        -7.0123443603515625,
        0.23151956498622894,
        -113.45040750775506
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            100,
            4,
            40
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "1bd67066-ee3f-4c13-ae74-0fccdc894678": {
      "name": "Kill",
      "tags": [
        "Kill"
      ],
      "enabled": true,
      "resource_id": "1bd67066-ee3f-4c13-ae74-0fccdc894678",
      "parent": "7ebea48a-0275-4c9d-8807-98d8728ee864",
      "children": [],
      "position": [
        -27.87889862060547,
        0.23151956498622894,
        -41.09221051839896
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            15,
            4,
            20
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "ccdc80d1-748c-4f12-8507-fb76f7021ed9": {
      "name": "jar_big_blue",
      "tags": [],
      "enabled": true,
      "resource_id": "ccdc80d1-748c-4f12-8507-fb76f7021ed9",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "4488d9de-6b57-406d-b384-cf5364f21dc5"
      ],
      "position": [
        74.7642845252121,
        14.284503936767578,
        -12.952122688293457
      ],
      "rotation": [
        0,
        -42.974161702400274,
        0
      ],
      "scale": [
        3.053023543319021,
        3.053023543319021,
        3.053023543319021
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 30018396,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "4488d9de-6b57-406d-b384-cf5364f21dc5": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Ceramic"
      ],
      "enabled": true,
      "resource_id": "4488d9de-6b57-406d-b384-cf5364f21dc5",
      "parent": "ccdc80d1-748c-4f12-8507-fb76f7021ed9",
      "children": [],
      "position": [
        -1.4128909242572263e-7,
        0.42909895338904663,
        0.0000011486024504847592
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "capsule",
          "halfExtents": [
            0.8,
            1,
            0.8
          ],
          "radius": 1,
          "axis": 1,
          "height": 3.2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "80c0977f-02cc-4f30-b5a9-3044a9cb59e3": {
      "name": "Grass",
      "tags": [],
      "enabled": true,
      "resource_id": "80c0977f-02cc-4f30-b5a9-3044a9cb59e3",
      "parent": "07cf7750-86ee-4886-a513-6f064142f725",
      "children": [],
      "position": [
        14.471187876248703,
        0,
        1.6347448825836182
      ],
      "rotation": [
        0,
        51.874141628465665,
        0
      ],
      "scale": [
        0.7080669997335788,
        0.7080669997335788,
        0.7080669997335788
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 31441653,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100011
        }
      }
    },
    "530085dd-2cd2-44fa-9671-aaf03c491407": {
      "name": "CameraPoints",
      "tags": [],
      "enabled": true,
      "resource_id": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "parent": "6d984d2f-ab17-42b9-b521-7b1bfb7da4ca",
      "children": [
        "7e14dd6c-c780-4cf6-9bbf-f9168d18308d",
        "807a177f-e3a2-40e6-b89b-2225936ee992",
        "0bb748d8-3b9f-4fc4-94ac-6f436c030d00",
        "b065ebdf-454d-4ad7-9936-37047ea99e53",
        "0887c959-6101-40a6-97fd-0e6ce279d09c",
        "9719125a-95c0-4d32-acfd-276800732362",
        "6478cd03-56c6-4bd5-8fd8-6d622a8803d2",
        "a8c7c499-eaec-4388-9c7d-ec427d34b088",
        "e9da93e5-1d33-42b0-81df-5ec51f297ca3",
        "472909b5-5efa-4582-b518-e77ce605d62a",
        "a906ce51-6f7a-4e11-8619-b3652aec0a17",
        "c413ab6c-e6bc-44f2-855d-f77ba4ac532d",
        "bfc4c935-f0e6-4dc9-b962-fe1b9283bc11",
        "f4e57a8e-f29a-44d5-9ffa-15583570d07f",
        "c7edd6c2-e7e1-4cd2-a6b5-1a09578abe16",
        "53840159-fdd1-4f25-b485-a2e1126199ba",
        "1128aea4-8e61-4892-922b-1ba482b5e361"
      ],
      "position": [
        0,
        0,
        0
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "7e14dd6c-c780-4cf6-9bbf-f9168d18308d": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "7e14dd6c-c780-4cf6-9bbf-f9168d18308d",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        23.759008407592773,
        18.444819000875864,
        34.18592071533203
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "807a177f-e3a2-40e6-b89b-2225936ee992": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "807a177f-e3a2-40e6-b89b-2225936ee992",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        69.78248596191406,
        22.413841247558594,
        -1.8829585741069648
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "0bb748d8-3b9f-4fc4-94ac-6f436c030d00": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "0bb748d8-3b9f-4fc4-94ac-6f436c030d00",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        -0.9018641710281372,
        19.492645263671875,
        -51.85239562666342
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "e9da93e5-1d33-42b0-81df-5ec51f297ca3": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "e9da93e5-1d33-42b0-81df-5ec51f297ca3",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        -75.81807216625131,
        21.929656982421875,
        28.227602005004883
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "472909b5-5efa-4582-b518-e77ce605d62a": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "472909b5-5efa-4582-b518-e77ce605d62a",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        -38.69746398925781,
        21.929656982421875,
        51.66567822520686
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "a906ce51-6f7a-4e11-8619-b3652aec0a17": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "a906ce51-6f7a-4e11-8619-b3652aec0a17",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        25.7397403717041,
        20.604528389020672,
        -16.885643005371094
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "c413ab6c-e6bc-44f2-855d-f77ba4ac532d": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "c413ab6c-e6bc-44f2-855d-f77ba4ac532d",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        30.020606994628906,
        20.604528427124023,
        -107.53096448882583
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "bfc4c935-f0e6-4dc9-b962-fe1b9283bc11": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "bfc4c935-f0e6-4dc9-b962-fe1b9283bc11",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        12.01620798847487,
        20.604528427124023,
        -134.48631286621094
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "f4e57a8e-f29a-44d5-9ffa-15583570d07f": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "f4e57a8e-f29a-44d5-9ffa-15583570d07f",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        -48.147576592883446,
        24.948476791381836,
        -144.2412109375
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "c7edd6c2-e7e1-4cd2-a6b5-1a09578abe16": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "c7edd6c2-e7e1-4cd2-a6b5-1a09578abe16",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        -86.47173459480295,
        12.437285423278809,
        -52.19808578491211
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "1128aea4-8e61-4892-922b-1ba482b5e361": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "1128aea4-8e61-4892-922b-1ba482b5e361",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        -41.11120213056193,
        27.65567970275879,
        -64.96743774414062
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "b065ebdf-454d-4ad7-9936-37047ea99e53": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "b065ebdf-454d-4ad7-9936-37047ea99e53",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        -65.31482111510228,
        11.34752082824707,
        -13.122669219970703
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "0887c959-6101-40a6-97fd-0e6ce279d09c": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "0887c959-6101-40a6-97fd-0e6ce279d09c",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        50.22972421063098,
        7.428329944610596,
        20.472097396850586
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "9719125a-95c0-4d32-acfd-276800732362": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "9719125a-95c0-4d32-acfd-276800732362",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        24.507728576660156,
        19.706641870351138,
        -68.6117935180664
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "6478cd03-56c6-4bd5-8fd8-6d622a8803d2": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "6478cd03-56c6-4bd5-8fd8-6d622a8803d2",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        42.66080829663021,
        19.706642150878906,
        -48.68144607543945
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "a8c7c499-eaec-4388-9c7d-ec427d34b088": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "a8c7c499-eaec-4388-9c7d-ec427d34b088",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        -80.37817166703157,
        9.026748657226562,
        -23.509784698486328
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "53840159-fdd1-4f25-b485-a2e1126199ba": {
      "name": "Point",
      "tags": [
        "CameraPoint"
      ],
      "enabled": true,
      "resource_id": "53840159-fdd1-4f25-b485-a2e1126199ba",
      "parent": "530085dd-2cd2-44fa-9671-aaf03c491407",
      "children": [],
      "position": [
        -57.69962054184114,
        21.49022674560547,
        -106.47925567626953
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "b2d09f4d-e2f4-40a6-8f5a-d4cce370535e": {
      "name": "Kill",
      "tags": [
        "Kill"
      ],
      "enabled": true,
      "resource_id": "b2d09f4d-e2f4-40a6-8f5a-d4cce370535e",
      "parent": "7ebea48a-0275-4c9d-8807-98d8728ee864",
      "children": [],
      "position": [
        -131.1075585722919,
        0.23151956498622894,
        -17.325748443603516
      ],
      "rotation": [
        360,
        -90,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            100,
            4,
            40
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "9a332baa-42ae-4b90-b2ed-110b577ebb43": {
      "name": "Collision",
      "tags": [
        "Rigidbody"
      ],
      "enabled": true,
      "resource_id": "9a332baa-42ae-4b90-b2ed-110b577ebb43",
      "parent": "22e89aa3-90ac-4029-baa8-0b841d039fa4",
      "children": [],
      "position": [
        -0.747636269790122,
        0.8297165719173891,
        -5.365679286983634
      ],
      "rotation": [
        0,
        -29.624870616487275,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            4,
            9,
            4
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "054d2c30-4353-4818-b99d-27546705b527": {
      "name": "Cards",
      "tags": [],
      "enabled": true,
      "resource_id": "054d2c30-4353-4818-b99d-27546705b527",
      "parent": "a84eb64b-ae5c-49f9-bb7c-a0746aae0286",
      "children": [
        "ec463146-e10b-475c-bab5-6a134a244542",
        "6edfec98-dbcd-4ad3-acb0-2d154e546911",
        "b8c49462-88ff-4689-b521-3a94a0b32d59",
        "68f8dd87-c6c5-42ab-ad01-af821f93e6ae"
      ],
      "position": [
        0,
        0,
        0
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "ec463146-e10b-475c-bab5-6a134a244542": {
      "name": "Plane",
      "tags": [],
      "enabled": true,
      "resource_id": "ec463146-e10b-475c-bab5-6a134a244542",
      "parent": "054d2c30-4353-4818-b99d-27546705b527",
      "children": [],
      "position": [
        -313.4526627218812,
        -19.59792122201855,
        386.0516871672994
      ],
      "rotation": [
        -89.99999999999997,
        15.27993359983885,
        180
      ],
      "scale": [
        768.1883581210491,
        240.49506745325849,
        360.31596774819286
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "plane",
          "asset": null,
          "materialAsset": 34345660,
          "castShadows": false,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100007
        }
      }
    },
    "b8c49462-88ff-4689-b521-3a94a0b32d59": {
      "name": "Plane",
      "tags": [],
      "enabled": true,
      "resource_id": "b8c49462-88ff-4689-b521-3a94a0b32d59",
      "parent": "054d2c30-4353-4818-b99d-27546705b527",
      "children": [],
      "position": [
        -486.476063823753,
        -12.99777084743808,
        -360.4266484892081
      ],
      "rotation": [
        89.99999999999991,
        77.83526629065497,
        -9.056113956817616e-14
      ],
      "scale": [
        949.7452852032914,
        240.49506745325849,
        240.49506745325849
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "plane",
          "asset": null,
          "materialAsset": 34345660,
          "castShadows": false,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100007
        }
      }
    },
    "6edfec98-dbcd-4ad3-acb0-2d154e546911": {
      "name": "Plane",
      "tags": [],
      "enabled": true,
      "resource_id": "6edfec98-dbcd-4ad3-acb0-2d154e546911",
      "parent": "054d2c30-4353-4818-b99d-27546705b527",
      "children": [],
      "position": [
        514.9775375630203,
        -60.32659026017969,
        -187.3822781688955
      ],
      "rotation": [
        89.99999999999993,
        -71.67473346777169,
        1.3150683908300077e-13
      ],
      "scale": [
        768.1883581210491,
        240.49506745325849,
        456.3023823009834
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "plane",
          "asset": null,
          "materialAsset": 34345660,
          "castShadows": false,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": 100007
        }
      }
    },
    "68f8dd87-c6c5-42ab-ad01-af821f93e6ae": {
      "name": "Plane",
      "tags": [],
      "enabled": true,
      "resource_id": "68f8dd87-c6c5-42ab-ad01-af821f93e6ae",
      "parent": "054d2c30-4353-4818-b99d-27546705b527",
      "children": [],
      "position": [
        0,
        -2.507576653236079,
        0
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1399.684861135645,
        1399.684861135645,
        1399.684861135645
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "plane",
          "asset": null,
          "materialAsset": 32160410,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "3a4dcdae-0818-45a0-a53d-281c5b37aa05": {
      "name": "Collision",
      "tags": [
        "Invisible"
      ],
      "enabled": true,
      "resource_id": "3a4dcdae-0818-45a0-a53d-281c5b37aa05",
      "parent": "8495f353-d6f2-4b63-bd87-991908ad65f3",
      "children": [],
      "position": [
        -0.9120473407529841,
        3.998767320572938,
        -9.376339863512213
      ],
      "rotation": [
        0,
        42.39363302423013,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            18.247,
            7,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "43875bbe-e14a-4172-95e8-825828cbc72c": {
      "name": "Collision2",
      "tags": [
        "Invisible"
      ],
      "enabled": true,
      "resource_id": "43875bbe-e14a-4172-95e8-825828cbc72c",
      "parent": "b1fbbb03-0c1c-480d-a1d5-6d83fdcdfaef",
      "children": [],
      "position": [
        -3.984285701545953,
        5,
        -6.377858881023712e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            18.792,
            5,
            9.5
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0
        }
      }
    },
    "e3917e02-315b-47cd-9e83-42b5ab6a10d3": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Grapple",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "e3917e02-315b-47cd-9e83-42b5ab6a10d3",
      "parent": "34bc34f4-408f-41b9-aebd-863cbfb8fad1",
      "children": [],
      "position": [
        0.00493076701637607,
        2.7327772953104272,
        -0.006462223699827074
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            11.5,
            2.5,
            3.165
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "8a126521-aece-4a14-98bf-3e9a88c529d2": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Grapple",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "8a126521-aece-4a14-98bf-3e9a88c529d2",
      "parent": "72dff8af-1a51-47fc-a3a4-30db7b6ab852",
      "children": [],
      "position": [
        0.00493076701637607,
        2.7327772953104272,
        -0.006462223699827074
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            11.5,
            2.5,
            3.165
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "6b4d7d3d-38de-4035-8802-3e6572c0d7ab": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Grapple",
        "Gravel"
      ],
      "enabled": true,
      "resource_id": "6b4d7d3d-38de-4035-8802-3e6572c0d7ab",
      "parent": "8acaa78b-8273-4a0e-96aa-d9a417ae8ef0",
      "children": [],
      "position": [
        0.00493076701637607,
        2.7327772953104272,
        -0.006462223699827074
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            11.5,
            2.5,
            3.165
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "801248bc-c1ba-4691-a3e4-c37e0ac9a009": {
      "name": "Collision",
      "tags": [
        "Rigidbody",
        "Brick",
        "Grapple"
      ],
      "enabled": true,
      "resource_id": "801248bc-c1ba-4691-a3e4-c37e0ac9a009",
      "parent": "4aa495c4-0f75-4dc9-be2d-db79e57efb4a",
      "children": [],
      "position": [
        -1.788139307734582e-7,
        5.514635235312782,
        2.3841858087791934e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.5,
            4.228,
            10.8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "8d6fe6bf-28dc-4498-9f73-cdd99e82f06c": {
      "name": "Collision",
      "tags": [
        "Invisible"
      ],
      "enabled": true,
      "resource_id": "8d6fe6bf-28dc-4498-9f73-cdd99e82f06c",
      "parent": "4aa495c4-0f75-4dc9-be2d-db79e57efb4a",
      "children": [],
      "position": [
        -1.788139307734582e-7,
        10.141037257940065,
        2.3841858087791934e-7
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "collision": {
          "enabled": true,
          "type": "box",
          "halfExtents": [
            6.5,
            9,
            10.8
          ],
          "radius": 0.5,
          "axis": 1,
          "height": 2,
          "asset": null
        },
        "rigidbody": {
          "enabled": true,
          "type": "static",
          "mass": 1,
          "linearDamping": 0,
          "angularDamping": 0,
          "linearFactor": [
            1,
            1,
            1
          ],
          "angularFactor": [
            1,
            1,
            1
          ],
          "friction": 0.5,
          "restitution": 0.5
        }
      }
    },
    "f0f505d5-95cb-4ee0-985e-1f71d11d807b": {
      "name": "Flag",
      "tags": [],
      "enabled": true,
      "resource_id": "f0f505d5-95cb-4ee0-985e-1f71d11d807b",
      "parent": "914189ba-f675-4bd2-a36a-c33de6cf47ee",
      "children": [
        "4dca8c8f-8a01-4c45-950a-21cff5a6ac84",
        "e778e173-841a-4f48-9ee1-277733d4aa45"
      ],
      "position": [
        24.430211379565726,
        31.469223810752172,
        -119.38030902747678
      ],
      "rotation": [
        86.18162905518818,
        -42.39870943511686,
        0.7432150766912088
      ],
      "scale": [
        1.6078779506281649,
        1.6078779506281649,
        1.6078779506281649
      ],
      "components": {}
    },
    "4dca8c8f-8a01-4c45-950a-21cff5a6ac84": {
      "name": "Flag-Animated",
      "tags": [],
      "enabled": true,
      "resource_id": "4dca8c8f-8a01-4c45-950a-21cff5a6ac84",
      "parent": "f0f505d5-95cb-4ee0-985e-1f71d11d807b",
      "children": [],
      "position": [
        -2.4614048938692817e-16,
        7.322484215761821e-16,
        -3.2977537185531274
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 34753212,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        },
        "script": {
          "enabled": true,
          "order": [
            "flagShader"
          ],
          "scripts": {
            "flagShader": {
              "enabled": true,
              "attributes": {
                "texture": 34753209
              }
            }
          }
        },
        "sound": {
          "enabled": true,
          "volume": 1,
          "pitch": 1,
          "positional": true,
          "refDistance": 8,
          "maxDistance": 10000,
          "rollOffFactor": 1,
          "distanceModel": "exponential",
          "slots": {
            "1": {
              "name": "Flap",
              "loop": true,
              "autoPlay": true,
              "overlap": false,
              "asset": 34753429,
              "startTime": 0,
              "duration": null,
              "volume": 0.82,
              "pitch": 0.9
            }
          }
        }
      }
    },
    "e778e173-841a-4f48-9ee1-277733d4aa45": {
      "name": "Flag-Pole",
      "tags": [],
      "enabled": true,
      "resource_id": "e778e173-841a-4f48-9ee1-277733d4aa45",
      "parent": "f0f505d5-95cb-4ee0-985e-1f71d11d807b",
      "children": [],
      "position": [
        1.3025735359837465e-16,
        -1.4475288391113286,
        1.7451700710332352
      ],
      "rotation": [
        -76.67419175751759,
        3.669462664781194e-15,
        4.233188314154695e-15
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 34753184,
          "materialAsset": null,
          "castShadows": true,
          "castShadowsLightmap": true,
          "receiveShadows": true,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        }
      }
    },
    "24f386f4-26c1-4f50-8f1e-ad85d1a9dad3": {
      "name": "Animated",
      "tags": [],
      "enabled": true,
      "resource_id": "24f386f4-26c1-4f50-8f1e-ad85d1a9dad3",
      "parent": "6d984d2f-ab17-42b9-b521-7b1bfb7da4ca",
      "children": [
        "5b092a2e-cc83-43e4-873b-3faecee3dc0b",
        "c9e62d19-b830-4a26-9f0f-20c4530e937f",
        "53d0378a-7d7a-43ad-903f-879e61136e1e",
        "35e23c3d-c8b3-48ca-9651-95b92b013935",
        "c0830f21-7030-4306-903e-54538d4d570d",
        "fa3b763b-c176-44df-a123-9b830f080c12",
        "f534f048-7448-4101-82e1-0d142d87fee4"
      ],
      "position": [
        0,
        0,
        0
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {}
    },
    "5b092a2e-cc83-43e4-873b-3faecee3dc0b": {
      "name": "Bird",
      "tags": [
        "Bird"
      ],
      "enabled": true,
      "resource_id": "5b092a2e-cc83-43e4-873b-3faecee3dc0b",
      "parent": "24f386f4-26c1-4f50-8f1e-ad85d1a9dad3",
      "children": [],
      "position": [
        12.24605655670166,
        4.133633613586426,
        3.3260147394753483
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        3.125181243043,
        3.125181243043,
        3.125181243043
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 38228935,
          "materialAsset": null,
          "castShadows": false,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        },
        "animation": {
          "enabled": true,
          "assets": [
            38228977,
            38231111
          ],
          "speed": 1,
          "loop": true,
          "activate": true
        },
        "sound": {
          "enabled": true,
          "volume": 1,
          "pitch": 1,
          "positional": true,
          "refDistance": 1,
          "maxDistance": 10000,
          "rollOffFactor": 1,
          "distanceModel": "linear",
          "slots": {
            "1": {
              "name": "Fly",
              "loop": false,
              "autoPlay": false,
              "overlap": false,
              "asset": 38230939,
              "startTime": 0,
              "duration": null,
              "volume": 1,
              "pitch": 1
            }
          }
        }
      }
    },
    "53d0378a-7d7a-43ad-903f-879e61136e1e": {
      "name": "Bird",
      "tags": [
        "Bird"
      ],
      "enabled": true,
      "resource_id": "53d0378a-7d7a-43ad-903f-879e61136e1e",
      "parent": "24f386f4-26c1-4f50-8f1e-ad85d1a9dad3",
      "children": [],
      "position": [
        13.42833234086308,
        4.133633613586426,
        4.7860822677612305
      ],
      "rotation": [
        0,
        -45.020820710233224,
        0
      ],
      "scale": [
        3.125181243043,
        3.125181243043,
        3.125181243043
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 38228935,
          "materialAsset": null,
          "castShadows": false,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        },
        "animation": {
          "enabled": true,
          "assets": [
            38228977,
            38231111
          ],
          "speed": 1,
          "loop": true,
          "activate": true
        }
      }
    },
    "c0830f21-7030-4306-903e-54538d4d570d": {
      "name": "Bird",
      "tags": [
        "Bird"
      ],
      "enabled": true,
      "resource_id": "c0830f21-7030-4306-903e-54538d4d570d",
      "parent": "24f386f4-26c1-4f50-8f1e-ad85d1a9dad3",
      "children": [],
      "position": [
        11.52984619140625,
        4.133633613586426,
        5.276614697734532
      ],
      "rotation": [
        0,
        -79.8046895881471,
        0
      ],
      "scale": [
        3.125181243043,
        3.125181243043,
        3.125181243043
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 38228935,
          "materialAsset": null,
          "castShadows": false,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        },
        "animation": {
          "enabled": true,
          "assets": [
            38228977,
            38231111
          ],
          "speed": 1,
          "loop": true,
          "activate": true
        }
      }
    },
    "fa3b763b-c176-44df-a123-9b830f080c12": {
      "name": "Bird",
      "tags": [
        "Bird"
      ],
      "enabled": true,
      "resource_id": "fa3b763b-c176-44df-a123-9b830f080c12",
      "parent": "24f386f4-26c1-4f50-8f1e-ad85d1a9dad3",
      "children": [],
      "position": [
        -13.662389812056881,
        14.417471885681152,
        -111.67303051350065
      ],
      "rotation": [
        180,
        -25.957539141637994,
        180
      ],
      "scale": [
        3.125181243043,
        3.125181243043,
        3.125181243043
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 38228935,
          "materialAsset": null,
          "castShadows": false,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        },
        "animation": {
          "enabled": true,
          "assets": [
            38228977,
            38231111
          ],
          "speed": 1,
          "loop": true,
          "activate": true
        }
      }
    },
    "35e23c3d-c8b3-48ca-9651-95b92b013935": {
      "name": "Bird",
      "tags": [
        "Bird"
      ],
      "enabled": true,
      "resource_id": "35e23c3d-c8b3-48ca-9651-95b92b013935",
      "parent": "24f386f4-26c1-4f50-8f1e-ad85d1a9dad3",
      "children": [],
      "position": [
        -12.674587835122772,
        14.417471885681152,
        -109.9791847442213
      ],
      "rotation": [
        180,
        -60.741408617332375,
        180
      ],
      "scale": [
        3.125181243043,
        3.125181243043,
        3.125181243043
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 38228935,
          "materialAsset": null,
          "castShadows": false,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        },
        "animation": {
          "enabled": true,
          "assets": [
            38228977,
            38231111
          ],
          "speed": 1,
          "loop": true,
          "activate": true
        },
        "sound": {
          "enabled": true,
          "volume": 1,
          "pitch": 1,
          "positional": true,
          "refDistance": 1,
          "maxDistance": 10000,
          "rollOffFactor": 1,
          "distanceModel": "linear",
          "slots": {
            "1": {
              "name": "Fly",
              "loop": false,
              "autoPlay": false,
              "overlap": false,
              "asset": 38230939,
              "startTime": 0,
              "duration": null,
              "volume": 1,
              "pitch": 1
            }
          }
        }
      }
    },
    "c9e62d19-b830-4a26-9f0f-20c4530e937f": {
      "name": "Bird",
      "tags": [
        "Bird"
      ],
      "enabled": true,
      "resource_id": "c9e62d19-b830-4a26-9f0f-20c4530e937f",
      "parent": "24f386f4-26c1-4f50-8f1e-ad85d1a9dad3",
      "children": [],
      "position": [
        -11.590583849971916,
        14.417471885681152,
        -111.51361962751419
      ],
      "rotation": [
        0,
        -74.23777060252046,
        0
      ],
      "scale": [
        3.125181243043,
        3.125181243043,
        3.125181243043
      ],
      "components": {
        "model": {
          "enabled": true,
          "type": "asset",
          "asset": 38228935,
          "materialAsset": null,
          "castShadows": false,
          "castShadowsLightmap": false,
          "receiveShadows": false,
          "lightmapped": false,
          "lightmapSizeMultiplier": 1,
          "castShadowsLightMap": true,
          "lightMapped": false,
          "lightMapSizeMultiplier": 1,
          "isStatic": false,
          "layers": [
            0
          ],
          "batchGroupId": null
        },
        "animation": {
          "enabled": true,
          "assets": [
            38228977,
            38231111
          ],
          "speed": 1,
          "loop": true,
          "activate": true
        }
      }
    },
    "f534f048-7448-4101-82e1-0d142d87fee4": {
      "name": "Birds",
      "tags": [],
      "enabled": true,
      "resource_id": "f534f048-7448-4101-82e1-0d142d87fee4",
      "parent": "24f386f4-26c1-4f50-8f1e-ad85d1a9dad3",
      "children": [
        "f86a9998-c919-4a5e-817d-2595e5a454b9"
      ],
      "position": [
        -14.205794334411621,
        2.7567659662214652e-14,
        -29.334165573120117
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        1,
        1,
        1
      ],
      "components": {
        "script": {
          "enabled": true,
          "order": [
            "rotate"
          ],
          "scripts": {
            "rotate": {
              "enabled": true,
              "attributes": {
                "axis": "y",
                "speed": 0.3,
                "waveStyle": false,
                "waveWidth": 0,
                "children": false,
                "graphName": ""
              }
            }
          }
        }
      }
    },
    "f86a9998-c919-4a5e-817d-2595e5a454b9": {
      "name": "Sprite",
      "tags": [],
      "enabled": true,
      "resource_id": "f86a9998-c919-4a5e-817d-2595e5a454b9",
      "parent": "f534f048-7448-4101-82e1-0d142d87fee4",
      "children": [],
      "position": [
        -24.64213275909424,
        110.53532409667966,
        209.83675913763156
      ],
      "rotation": [
        0,
        0,
        0
      ],
      "scale": [
        15.922340546700799,
        15.922340546700799,
        15.922340546700799
      ],
      "components": {
        "sprite": {
          "enabled": true,
          "type": "animated",
          "width": 1,
          "height": 1,
          "color": [
            0,
            0,
            0
          ],
          "opacity": 1,
          "flipX": false,
          "flipY": false,
          "spriteAsset": null,
          "frame": 0,
          "speed": 1,
          "batchGroupId": null,
          "layers": [
            0
          ],
          "drawOrder": 0,
          "autoPlayClip": "Birds",
          "clips": {
            "0": {
              "name": "Birds",
              "fps": 4,
              "loop": true,
              "autoPlay": true,
              "spriteAsset": 34049340
            }
          }
        }
      }
    }
  },
  "created": "2020-10-31T15:42:25.501Z",
  "id": 1024036
}
