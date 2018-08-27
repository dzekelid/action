---
swagger: "2.0"
x-collection-name: AWS Identity and Access Management
x-complete: 0
info:
  title: AWS Identity and Access Management API Delete Signing Certificate
  version: 1.0.0
  description: Deletes a signing certificate associated with the specified IAM user.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddClientIDToOpenIDConnectProvider:
    get:
      summary: Add Client I D To Open I D Connect Provider
      description: |-
        Adds a new client ID (also known as audience) to the list of client IDs already
              registered for the specified IAM OpenID Connect (OIDC) provider resource.
      operationId: addClientIDToOpenIDConnectProvider
      x-api-path-slug: actionaddclientidtoopenidconnectprovider-get
      parameters:
      - in: query
        name: ClientID
        description: The client ID (also known as audience) to add to the IAM OpenID
          Connect provider      resource
        type: string
      - in: query
        name: OpenIDConnectProviderArn
        description: The Amazon Resource Name (ARN) of the IAM OpenID Connect (OIDC)
          provider resource to      add the client ID to
        type: string
      responses:
        200:
          description: OK
      tags:
      - OpenID Connect Providers
  /?Action=AddRoleToInstanceProfile:
    get:
      summary: Add Role To Instance Profile
      description: Adds the specified IAM role to the specified instance profile.
      operationId: addRoleToInstanceProfile
      x-api-path-slug: actionaddroletoinstanceprofile-get
      parameters:
      - in: query
        name: InstanceProfileName
        description: The name of the instance profile to update
        type: string
      - in: query
        name: RoleName
        description: The name of the role to add
        type: string
      responses:
        200:
          description: OK
      tags:
      - Role Instance
  /?Action=AddUserToGroup:
    get:
      summary: Add User To Group
      description: Adds the specified user to the specified group.
      operationId: addUserToGroup
      x-api-path-slug: actionaddusertogroup-get
      parameters:
      - in: query
        name: GroupName
        description: The name of the group to update
        type: string
      - in: query
        name: UserName
        description: The name of the user to add
        type: string
      responses:
        200:
          description: OK
      tags:
      - User Groups
  /?Action=AttachGroupPolicy:
    get:
      summary: Attach Group Policy
      description: Attaches the specified managed policy to the specified IAM group.
      operationId: attachGroupPolicy
      x-api-path-slug: actionattachgrouppolicy-get
      parameters:
      - in: query
        name: GroupName
        description: The name (friendly name, not ARN) of the group to attach the
          policy to
        type: string
      - in: query
        name: PolicyArn
        description: The Amazon Resource Name (ARN) of the IAM policy you want to
          attach
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group Policies
  /?Action=AttachRolePolicy:
    get:
      summary: Attach Role Policy
      description: Attaches the specified managed policy to the specified IAM role.
      operationId: attachRolePolicy
      x-api-path-slug: actionattachrolepolicy-get
      parameters:
      - in: query
        name: PolicyArn
        description: The Amazon Resource Name (ARN) of the IAM policy you want to
          attach
        type: string
      - in: query
        name: RoleName
        description: The name (friendly name, not ARN) of the role to attach the policy
          to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Role Policies
  /?Action=AttachUserPolicy:
    get:
      summary: Attach User Policy
      description: Attaches the specified managed policy to the specified user.
      operationId: attachUserPolicy
      x-api-path-slug: actionattachuserpolicy-get
      parameters:
      - in: query
        name: PolicyArn
        description: The Amazon Resource Name (ARN) of the IAM policy you want to
          attach
        type: string
      - in: query
        name: UserName
        description: The name (friendly name, not ARN) of the IAM user to attach the
          policy to
        type: string
      responses:
        200:
          description: OK
      tags:
      - User Policies
  /?Action=ChangePassword:
    get:
      summary: Change Password
      description: Changes the password of the IAM user who is calling this action.
      operationId: changePassword
      x-api-path-slug: actionchangepassword-get
      parameters:
      - in: query
        name: NewPassword
        description: The new password
        type: string
      - in: query
        name: OldPassword
        description: The IAM users current password
        type: string
      responses:
        200:
          description: OK
      tags:
      - Passwords
  /?Action=CreateAccessKey:
    get:
      summary: Create Access Key
      description: |-
        Creates a new AWS secret access key and corresponding AWS access key ID for the
              specified user.
      operationId: createAccessKey
      x-api-path-slug: actioncreateaccesskey-get
      parameters:
      - in: query
        name: UserName
        description: The name of the IAM user that the new key will belong to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Access Keys
  /?Action=CreateAccountAlias:
    get:
      summary: Create Account Alias
      description: Creates an alias for your AWS account.
      operationId: createAccountAlias
      x-api-path-slug: actioncreateaccountalias-get
      parameters:
      - in: query
        name: AccountAlias
        description: The account alias to create
        type: string
      responses:
        200:
          description: OK
      tags:
      - Account Alias
  /?Action=CreateGroup:
    get:
      summary: Create Group
      description: Creates a new group.
      operationId: createGroup
      x-api-path-slug: actioncreategroup-get
      parameters:
      - in: query
        name: GroupName
        description: The name of the group to create
        type: string
      - in: query
        name: Path
        description: The path to the group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Groups
  /?Action=CreateInstanceProfile:
    get:
      summary: Create Instance Profile
      description: Creates a new instance profile.
      operationId: createInstanceProfile
      x-api-path-slug: actioncreateinstanceprofile-get
      parameters:
      - in: query
        name: InstanceProfileName
        description: The name of the instance profile to create
        type: string
      - in: query
        name: Path
        description: The path to the instance profile
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instance Profiles
  /?Action=CreateLoginProfile:
    get:
      summary: Create Login Profile
      description: |-
        Creates a password for the specified user, giving the user the ability to access AWS
              services through the AWS Management Console.
      operationId: createLoginProfile
      x-api-path-slug: actioncreateloginprofile-get
      parameters:
      - in: query
        name: Password
        description: The new password for the user
        type: string
      - in: query
        name: PasswordResetRequired
        description: Specifies whether the user is required to set a new password
          on next sign-in
        type: string
      - in: query
        name: UserName
        description: The name of the IAM user to create a password for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Login Profiles
  /?Action=CreateOpenIDConnectProvider:
    get:
      summary: Create Open I D Connect Provider
      description: Creates an IAM entity to describe an identity provider (IdP) that
        supports.
      operationId: createOpenIDConnectProvider
      x-api-path-slug: actioncreateopenidconnectprovider-get
      parameters:
      - in: query
        name: ClientIDList.member.N
        description: A list of client IDs (also known as audiences)
        type: string
      - in: query
        name: ThumbprintList.member.N
        description: A list of server certificate thumbprints for the OpenID Connect
          (OIDC) identity      providers server certificate(s)
        type: string
      - in: query
        name: Url
        description: The URL of the identity provider
        type: string
      responses:
        200:
          description: OK
      tags:
      - OpenID Connect Providers
  /?Action=CreatePolicy:
    get:
      summary: Create Policy
      description: Creates a new managed policy for your AWS account.
      operationId: createPolicy
      x-api-path-slug: actioncreatepolicy-get
      parameters:
      - in: query
        name: Description
        description: A friendly description of the policy
        type: string
      - in: query
        name: Path
        description: The path for the policy
        type: string
      - in: query
        name: PolicyDocument
        description: The JSON policy document that you want to use as the content
          for the new      policy
        type: string
      - in: query
        name: PolicyName
        description: The friendly name of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
  /?Action=CreatePolicyVersion:
    get:
      summary: Create Policy Version
      description: Creates a new version of the specified managed policy.
      operationId: createPolicyVersion
      x-api-path-slug: actioncreatepolicyversion-get
      parameters:
      - in: query
        name: PolicyArn
        description: The Amazon Resource Name (ARN) of the IAM policy to which you
          want to add a new      version
        type: string
      - in: query
        name: PolicyDocument
        description: The JSON policy document that you want to use as the content
          for this new version of      the policy
        type: string
      - in: query
        name: SetAsDefault
        description: Specifies whether to set this version as the policys default
          version
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
  /?Action=CreateRole:
    get:
      summary: Create Role
      description: Creates a new role for your AWS account.
      operationId: createRole
      x-api-path-slug: actioncreaterole-get
      parameters:
      - in: query
        name: AssumeRolePolicyDocument
        description: The trust relationship policy document that grants an entity
          permission to assume the      role
        type: string
      - in: query
        name: Path
        description: The path to the role
        type: string
      - in: query
        name: RoleName
        description: The name of the role to create
        type: string
      responses:
        200:
          description: OK
      tags:
      - Roles
  /?Action=CreateSAMLProvider:
    get:
      summary: Create S A M L Provider
      description: |-
        Creates an IAM resource that describes an identity provider (IdP) that supports SAML
              2.
      operationId: createSAMLProvider
      x-api-path-slug: actioncreatesamlprovider-get
      parameters:
      - in: query
        name: Name
        description: The name of the provider to create
        type: string
      - in: query
        name: SAMLMetadataDocument
        description: An XML document generated by an identity provider (IdP) that
          supports SAML 2
        type: string
      responses:
        200:
          description: OK
      tags:
      - SAML Providers
  /?Action=CreateServiceSpecificCredential:
    get:
      summary: Create Service Specific Credential
      description: |-
        Generates a set of credentials consisting of a user name and password that can be used
              to access the service specified in the request.
      operationId: createServiceSpecificCredential
      x-api-path-slug: actioncreateservicespecificcredential-get
      parameters:
      - in: query
        name: ServiceName
        description: The name of the AWS service that is to be associated with the
          credentials
        type: string
      - in: query
        name: UserName
        description: The name of the IAM user that is to be associated with the credentials
        type: string
      responses:
        200:
          description: OK
      tags:
      - Service Specific Credentials
  /?Action=CreateUser:
    get:
      summary: Create User
      description: Creates a new IAM user for your AWS account.
      operationId: createUser
      x-api-path-slug: actioncreateuser-get
      parameters:
      - in: query
        name: Path
        description: The path for the user name
        type: string
      - in: query
        name: UserName
        description: The name of the user to create
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
  /?Action=CreateVirtualMFADevice:
    get:
      summary: Create Virtual M F A Device
      description: Creates a new virtual MFA device for the AWS account.
      operationId: createVirtualMFADevice
      x-api-path-slug: actioncreatevirtualmfadevice-get
      parameters:
      - in: query
        name: Path
        description: The path for the virtual MFA device
        type: string
      - in: query
        name: VirtualMFADeviceName
        description: The name of the virtual MFA device
        type: string
      responses:
        200:
          description: OK
      tags:
      - Virtual MFA Device
  /?Action=DeactivateMFADevice:
    get:
      summary: Deactivate M F A Device
      description: |-
        Deactivates the specified MFA device and removes it from association with the user name
              for which it was originally enabled.
      operationId: deactivateMFADevice
      x-api-path-slug: actiondeactivatemfadevice-get
      parameters:
      - in: query
        name: SerialNumber
        description: The serial number that uniquely identifies the MFA device
        type: string
      - in: query
        name: UserName
        description: The name of the user whose MFA device you want to deactivate
        type: string
      responses:
        200:
          description: OK
      tags:
      - Virtual MFA Device
  /?Action=DeleteAccessKey:
    get:
      summary: Delete Access Key
      description: Deletes the access key pair associated with the specified IAM user.
      operationId: deleteAccessKey
      x-api-path-slug: actiondeleteaccesskey-get
      parameters:
      - in: query
        name: AccessKeyId
        description: The access key ID for the access key ID and secret access key
          you want to      delete
        type: string
      - in: query
        name: UserName
        description: The name of the user whose access key pair you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Access Keys
  /?Action=DeleteAccountAlias:
    get:
      summary: Delete Account Alias
      description: Deletes the specified AWS account alias.
      operationId: deleteAccountAlias
      x-api-path-slug: actiondeleteaccountalias-get
      parameters:
      - in: query
        name: AccountAlias
        description: The name of the account alias to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Account Alias
  /?Action=DeleteAccountPasswordPolicy:
    get:
      summary: Delete Account Password Policy
      description: Deletes the password policy for the AWS account.
      operationId: deleteAccountPasswordPolicy
      x-api-path-slug: actiondeleteaccountpasswordpolicy-get
      parameters:
      - in: query
        name: LimitExceeded
        description: The request was rejected because it attempted to create resources
          beyond the current      AWS account limits
        type: string
      - in: query
        name: NoSuchEntity
        description: The request was rejected because it referenced an entity that
          does not exist
        type: string
      - in: query
        name: ServiceFailure
        description: The request processing has failed because of an unknown error,
          exception or      failure
        type: string
      responses:
        200:
          description: OK
      tags:
      - Account Password Policies
  /?Action=DeleteGroup:
    get:
      summary: Delete Group
      description: Deletes the specified IAM group.
      operationId: deleteGroup
      x-api-path-slug: actiondeletegroup-get
      parameters:
      - in: query
        name: GroupName
        description: The name of the IAM group to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Groups
  /?Action=DeleteGroupPolicy:
    get:
      summary: Delete Group Policy
      description: |-
        Deletes the specified inline policy that is embedded in the specified IAM
              group.
      operationId: deleteGroupPolicy
      x-api-path-slug: actiondeletegrouppolicy-get
      parameters:
      - in: query
        name: GroupName
        description: The name (friendly name, not ARN) identifying the group that
          the policy is embedded      in
        type: string
      - in: query
        name: PolicyName
        description: The name identifying the policy document to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group Policies
  /?Action=DeleteInstanceProfile:
    get:
      summary: Delete Instance Profile
      description: Deletes the specified instance profile.
      operationId: deleteInstanceProfile
      x-api-path-slug: actiondeleteinstanceprofile-get
      parameters:
      - in: query
        name: InstanceProfileName
        description: The name of the instance profile to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instance Profiles
  /?Action=DeleteLoginProfile:
    get:
      summary: Delete Login Profile
      description: |-
        Deletes the password for the specified IAM user, which terminates the user's ability
              to access AWS services through the AWS Management Console.
      operationId: deleteLoginProfile
      x-api-path-slug: actiondeleteloginprofile-get
      parameters:
      - in: query
        name: UserName
        description: The name of the user whose password you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Login Profiles
  /?Action=DeleteOpenIDConnectProvider:
    get:
      summary: Delete Open I D Connect Provider
      description: Deletes an OpenID Connect identity provider (IdP) resource object
        in IAM.
      operationId: deleteOpenIDConnectProvider
      x-api-path-slug: actiondeleteopenidconnectprovider-get
      parameters:
      - in: query
        name: OpenIDConnectProviderArn
        description: The Amazon Resource Name (ARN) of the IAM OpenID Connect provider
          resource object to      delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - OpenID Connect Providers
  /?Action=DeletePolicy:
    get:
      summary: Delete Policy
      description: Deletes the specified managed policy.
      operationId: deletePolicy
      x-api-path-slug: actiondeletepolicy-get
      parameters:
      - in: query
        name: PolicyArn
        description: The Amazon Resource Name (ARN) of the IAM policy you want to
          delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
  /?Action=DeletePolicyVersion:
    get:
      summary: Delete Policy Version
      description: Deletes the specified version from the specified managed policy.
      operationId: deletePolicyVersion
      x-api-path-slug: actiondeletepolicyversion-get
      parameters:
      - in: query
        name: PolicyArn
        description: The Amazon Resource Name (ARN) of the IAM policy from which you
          want to delete a      version
        type: string
      - in: query
        name: VersionId
        description: The policy version to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
  /?Action=DeleteRole:
    get:
      summary: Delete Role
      description: Deletes the specified role.
      operationId: deleteRole
      x-api-path-slug: actiondeleterole-get
      parameters:
      - in: query
        name: RoleName
        description: The name of the role to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Roles
  /?Action=DeleteRolePolicy:
    get:
      summary: Delete Role Policy
      description: |-
        Deletes the specified inline policy that is embedded in the specified IAM
              role.
      operationId: deleteRolePolicy
      x-api-path-slug: actiondeleterolepolicy-get
      parameters:
      - in: query
        name: PolicyName
        description: The name of the inline policy to delete from the specified IAM
          role
        type: string
      - in: query
        name: RoleName
        description: The name (friendly name, not ARN) identifying the role that the
          policy is embedded      in
        type: string
      responses:
        200:
          description: OK
      tags:
      - Role Policies
  /?Action=DeleteSAMLProvider:
    get:
      summary: Delete S A M L Provider
      description: Deletes a SAML provider resource in IAM.
      operationId: deleteSAMLProvider
      x-api-path-slug: actiondeletesamlprovider-get
      parameters:
      - in: query
        name: SAMLProviderArn
        description: The Amazon Resource Name (ARN) of the SAML provider to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - SAML Providers
  /?Action=DeleteServerCertificate:
    get:
      summary: Delete Server Certificate
      description: Deletes the specified server certificate.
      operationId: deleteServerCertificate
      x-api-path-slug: actiondeleteservercertificate-get
      parameters:
      - in: query
        name: ServerCertificateName
        description: The name of the server certificate you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Certificates
  /?Action=DeleteServiceSpecificCredential:
    get:
      summary: Delete Service Specific Credential
      description: Deletes the specified service-specific credential.
      operationId: deleteServiceSpecificCredential
      x-api-path-slug: actiondeleteservicespecificcredential-get
      parameters:
      - in: query
        name: ServiceSpecificCredentialId
        description: The unique identifier of the service-specific credential
        type: string
      - in: query
        name: UserName
        description: The name of the IAM user associated with the service-specific
          credential
        type: string
      responses:
        200:
          description: OK
      tags:
      - Service Specific Credentials
  /?Action=DeleteSigningCertificate:
    get:
      summary: Delete Signing Certificate
      description: Deletes a signing certificate associated with the specified IAM
        user.
      operationId: deleteSigningCertificate
      x-api-path-slug: actiondeletesigningcertificate-get
      parameters:
      - in: query
        name: CertificateId
        description: The ID of the signing certificate to delete
        type: string
      - in: query
        name: UserName
        description: The name of the user the signing certificate belongs to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Signing Certificates
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