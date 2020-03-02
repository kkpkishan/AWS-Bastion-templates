# AWS Bastion Server  CloudFormation Templates
<table width="100%">
    <tr>
        <th align="left" colspan="2"><h4><a href="https://github.com/kkpkishan/aws-Bastion-cloudformation-templates.git">Bastion</a></h4></th>
    </tr>
    <tr>
        <td width="100%" valign="top">
            <p>Creates a single Bastion host on a Public subnet in an existing VPC. Select from either a Centos, Ubuntu or Windows OS.</p>
            <h6>Prerequisites</h6>
            <ol>
             <li>VPC</li>
             <ul>
               <li>Public Subnet, IGW, Private Subnet/s.</li>
               <li>Either use an existing VPC Infrastructure or you can use the following <a href="https://github.com/kkpkishan/aws-vpc-cloudformation-Templates.git" target="_blank">VPC Template</a> to create a one.</li>
             </ul>
            <li>Available EIP</li>
            </ol>
            <h6>Create Details</h6>
            <ol>
             <li>EC2 Instance</li>
             <li>EIP</li>
             <li>IAM Role</li>
             <li>IAM Instance Profile</li>
             <li>Security Group</li>
            </ol>
        </td>
        <td  nowrap width="200" valign="top">
            </table>
