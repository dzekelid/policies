---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 0
info:
  title: AXA Assistance Gets the information linked to the policy holder of the home
    appliance damage declaration
  description: Gets the information linked to the policy holder of the home appliance
    damage declaration
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /assistance/v1/home/electric_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the policy holders details for the electric damage
      description: Gets the policy holders details for the electric damage
      operationId: getAssistanceV1HomeElectric_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homeelectric-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holderAssistance
      - detailsthe
      - electric
      - damage
  /assistance/v1/home/gas_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the policy holders details for the gas damage
      description: Gets the policy holders details for the gas damage
      operationId: getAssistanceV1HomeGas_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homegas-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holderAssistance
      - detailsthe
      - gaAssistance
      - damage
  /assistance/v1/home/glaziery_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information linked to the policy holder of the glaziery damage
        declaration
      description: Gets the information linked to the policy holder of the glaziery
        damage declaration
      operationId: getAssistanceV1HomeGlaziery_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homeglaziery-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - linked
      - to
      - the
      - policy
      - holder
      - of
      - the
      - glaziery
      - damage
      - Declarations
  /assistance/v1/home/home_appliance_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information linked to the policy holder of the home appliance
        damage declaration
      description: Gets the information linked to the policy holder of the home appliance
        damage declaration
      operationId: getAssistanceV1HomeHome_appliance_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homehome-appliance-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - linked
      - to
      - the
      - policy
      - holder
      - of
      - the
      - home
      - appliance
      - damage
      - Declarations
  /assistance/v1/home/locksmithing_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information linked to the policy holder of the locksmithing
        damage declaration
      description: Gets the information linked to the policy holder of the locksmithing
        damage declaration
      operationId: getAssistanceV1HomeLocksmithing_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homelocksmithing-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - linked
      - to
      - the
      - policy
      - holder
      - of
      - the
      - locksmithing
      - damage
      - Declarations
  /assistance/v1/home/water_damage/declarations/{declaration_id}/policy_holders:
    get:
      summary: Gets the information related to each the policy holder of the water
        damage declaration
      description: Gets the information related to each the policy holder of the water
        damage declaration
      operationId: getAssistanceV1HomeWater_damageDeclarationsDeclaration_idPolicy_holders
      x-api-path-slug: assistancev1homewater-damagedeclarationsdeclaration-idpolicy-holders-get
      parameters:
      - in: path
        name: declaration_id
        description: ID of the declaration
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - information
      - related
      - to
      - each
      - the
      - policy
      - holder
      - of
      - the
      - water
      - damage
      - Declarations
  /sales/vexp/individual/travel/policies/{policy_id}/cancel:
    post:
      summary: Cancel an existing policy
      description: Cancel an existing policy
      operationId: postSalesVexpIndividualTravelPoliciesPolicy_idCancel
      x-api-path-slug: salesvexpindividualtravelpoliciespolicy-idcancel-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: policy_id
        description: ID of the policy
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Cancelexisting
      - policy
  /assistance/v1/home/electric_damage/declarations/{declaration_id}/policy_holders/{policy_holder_id}:
    patch:
      summary: Updates the policy holder information of the electric damage declaration
      description: Updates the policy holder information of the electric damage declaration
      operationId: patchAssistanceV1HomeElectric_damageDeclarationsDeclaration_idPolicy_holdersPolicy_holder_id
      x-api-path-slug: assistancev1homeelectric-damagedeclarationsdeclaration-idpolicy-holderspolicy-holder-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      - in: path
        name: policy_holder_id
        description: ID of the policy holder
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holder
      - information
      - of
      - the
      - electric
      - damage
      - Declarations
  /assistance/v1/home/gas_damage/declarations/{declaration_id}/policy_holders/{policy_holder_id}:
    patch:
      summary: Updates the policy holder information of the gas damage declaration
      description: Updates the policy holder information of the gas damage declaration
      operationId: patchAssistanceV1HomeGas_damageDeclarationsDeclaration_idPolicy_holdersPolicy_holder_id
      x-api-path-slug: assistancev1homegas-damagedeclarationsdeclaration-idpolicy-holderspolicy-holder-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      - in: path
        name: policy_holder_id
        description: ID of the policy holder
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holder
      - information
      - of
      - the
      - gaAssistance
      - damage
      - Declarations
  /assistance/v1/home/glaziery_damage/declarations/{declaration_id}/policy_holders/{policy_holder_id}:
    patch:
      summary: Updates the policy holder information of the glaziery damage declaration
      description: Updates the policy holder information of the glaziery damage declaration
      operationId: patchAssistanceV1HomeGlaziery_damageDeclarationsDeclaration_idPolicy_holdersPolicy_holder_id
      x-api-path-slug: assistancev1homeglaziery-damagedeclarationsdeclaration-idpolicy-holderspolicy-holder-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      - in: path
        name: policy_holder_id
        description: ID of the policy holder
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holder
      - information
      - of
      - the
      - glaziery
      - damage
      - Declarations
  /assistance/v1/home/home_appliance_damage/declarations/{declaration_id}/policy_holders/{policy_holder_id}:
    patch:
      summary: Update the policy holder information of the home appliance damage declaration
      description: Update the policy holder information of the home appliance damage
        declaration
      operationId: patchAssistanceV1HomeHome_appliance_damageDeclarationsDeclaration_idPolicy_holdersPolicy_holder_id
      x-api-path-slug: assistancev1homehome-appliance-damagedeclarationsdeclaration-idpolicy-holderspolicy-holder-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      - in: path
        name: policy_holder_id
        description: ID of the policy holder
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - the
      - policy
      - holder
      - information
      - of
      - the
      - home
      - appliance
      - damage
      - Declarations
  /assistance/v1/home/locksmithing_damage/declarations/{declaration_id}/policy_holders/{policy_holder_id}:
    patch:
      summary: Updates the policy holder information of the locksmithing damage declaration
      description: Updates the policy holder information of the locksmithing damage
        declaration
      operationId: patchAssistanceV1HomeLocksmithing_damageDeclarationsDeclaration_idPolicy_holdersPolicy_holder_id
      x-api-path-slug: assistancev1homelocksmithing-damagedeclarationsdeclaration-idpolicy-holderspolicy-holder-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      - in: path
        name: policy_holder_id
        description: ID of the policy holder
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holder
      - information
      - of
      - the
      - locksmithing
      - damage
      - Declarations
  /assistance/v1/home/water_damage/declarations/{declaration_id}/policy_holders/{policy_holder_id}:
    patch:
      summary: Updates the policy holder information of the water damage declaration
      description: Updates the policy holder information of the water damage declaration
      operationId: patchAssistanceV1HomeWater_damageDeclarationsDeclaration_idPolicy_holdersPolicy_holder_id
      x-api-path-slug: assistancev1homewater-damagedeclarationsdeclaration-idpolicy-holderspolicy-holder-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: declaration_id
        description: ID of the declaration
      - in: path
        name: policy_holder_id
        description: ID of the policy holder
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - policy
      - holder
      - information
      - of
      - the
      - water
      - damage
      - Declarations
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---