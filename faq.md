# FAQ

<article class="section" markdown="1">
## Q: What are some use cases for data portability?

There are many use cases for users porting data directly between services, some we know about today, and some we have yet to discover. A couple of examples of ones we know users want today are:

**Creating online backups for bulk personal data** &mdash; Getting a backup of years' worth of photos and videos, in case anything goes wrong with an account or a service, is a precaution many people can't afford to take if local storage must be involved.  Backups to online cloud backup service ought to be widely available and easy to use.

**Trying out a new service** &mdash; Whether a user is moving an album worth of photos to an album printer, or testing a new music service or a service to track everything they read, it should be possible to port some or all of one's photos, playlists or reading history to try out the new service.

**Leaving a service** &mdash; A home-owner in a low-bandwidth area has been working with architects who have developed detailed drawings and plans for new buildings. When the project is over, there should be an easy way that doesn't consume all the home-owner's bandwidth to transfer the large project files to long-term cloud storage.

</article>

<article class="section" markdown="1">
## Q: What kinds of data can be transferred through DTP?

The terms of each organization’s API determine the data types that can be transferred between providers. This ordinarily includes data stored in a specific users’s account, but may not be limited to that data, depending on the organizations involved.  Additional or substitute functionality outside of the Data Transfer Project would be necessary for data transfers requiring particularly high integrity (e.g. health records).

</article>

<article class="section" markdown="1">
## Q: Who is responsible for protecting data before, during, and after the transfer takes place?

Each organization is responsible for securing and protecting the data stored on its platform, regardless of whether it is supporting a transfer out or receiving a transfer from another organization. Generally, this includes established practices in securing access, authorization, and authentication to public APIs or other mechanisms. Additionally, this includes writing and enforcing policies governing access to that information through an API or other mechanism. Those specific terms govern the conditions of transferring data into or out of each provider. Additionally, there are baseline security requirements detailed in the White Paper, such as  encryption in transit, that should always be adhered to.

</article>

<article class="section" markdown="1">
## Q: When data is transferred, do contributors to DTP or partners of the Data Transfer Initiative all get a copy?

No, when a user initiates a data transfer, their encrypted information flows from one provider directly to another that is chosen by the user. Only the source service, the destination service (and hosting provider, if it is not the source or destination service) have access to the data.  No other contributors or 3rd parties have access to a copy of the data as part of the transfer.

</article>

<article class="section" markdown="1">
## Q: Are there common standards by which contributors to the Data Transfer Project should abide in performing transfers?

As described in the white paper, DTP adheres to the following principles:

We believe the following principles around interoperability and portability of data promote user choice and encourage responsible product development, maximizing the benefits to users and mitigating the potential drawbacks.

  * **Build for users**: Data portability tools should be easy to find, intuitive to use, and readily available for users. They should also be open and interoperable with standard industry formats, where applicable, so that users can easily transfer data between services or download it for their own purposes.
  * **Privacy and security**: Providers on each side of the portability transaction should have strong privacy and security measures—such as encryption in transit—to guard against unauthorized access, diversion of data, or other types of fraud. It is important to apply privacy principles such as data minimization and transparency when transferring data between providers. When users initiate a transfer they should be told in a clear and concise manner about the types and scope of data being transferred as well as how the data will be used at the destination service. Users should also be advised about the privacy and security practices of the destination service. These measures will help to educate users about the data being transferred and how the data will be used at the destination service. More details are in the Security & Privacy section below.
  * **Reciprocity**: While portability offers more choice and flexibility for users, it will be important to guard against incentives that are misaligned with user interests. A user’s decision to move data to another service should not result in any loss of transparency or control over that data. Individuals should have assurance that data imported to a provider can likewise be exported again, if they so choose. Ultimately, users should be able to make informed choices about where to store their data. We believe that providing transparency around portability will lead to users preferring providers that are committed to reciprocal data portability, over those that are not.
  * **Focus on user’s data**: Portability efforts should emphasize data and use cases that support the individual user. Focusing on content a user creates, imports, approves for collection, or has control over reduces the friction for users who want to switch among products or services or use their data in novel ways, because the data they export is meaningful to them. Portability should not extend to data that may negatively impact the privacy of other users, or data collected to improve a service, including data generated to improve system performance or train models that may be commercially sensitive or proprietary. This approach encourages companies to continue to support data portability, knowing that their proprietary technologies are not threatened by data portability requirements. For a detailed taxonomy of such data, see ISO/IEC 19944:2017.
  * **Respect Everyone**: We live in a collaborative world: people connect and share on social media, they edit docs together, and they comment on videos, pictures and more. Data portability tools should focus only on providing data that is directly tied to the person requesting the transfer. We think this strikes the right balance between portability, privacy, and benefits of trying a new service.

</article>
