<link rel="stylesheet" href="table_hide.css"/>
<div class="metadata">
   <h2>Metadata</h2>
   <dl class="grid">
      <dt>Name:</dt>
      <dd>test-gt</dd>
      <dt>Description:</dt>
      <dd>Kurrent GT from the Moravian Knowledge Network handwritten periodicals</dd>
      <dt>Language:</dt>
      <dd>deu</dd>
      <dt>Format:</dt>
      <dd>Page-XML</dd>
      <dt>Production software:</dt>
      <dd>eScriptorium + Kraken</dd>
      <dt>Time:</dt>
      <dd>1765-1806</dd>
      <dt>GT Type:</dt>
      <dd>data_structure_and_text</dd>
   </dl>
   <details>
      <summary>More Information</summary>
      <dl class="more-grid">
         <dt>Transcription Guidelines:</dt>
         <dd>OCR-D GT Level 2, but with ℓ as </dd>
         <dt>License:</dt>
         <dd>PublicDomainMark 1.0</dd>
         <dt>Project:</dt>
         <dd>Gemein-Nachrichten der Herrnhuter Brüdergemeine</dd>
         <dt>Project-URL:</dt>
         <dd>https://dhh.hypotheses.org/</dd>
      </dl>
   </details>
</div>
<div class="metadata">
   <h2>Labelling</h2>
   <p>The GT data has been labeled. The labeling is 
               based on an ontology defined by the Pattern Recognition and Image Analysis Research Lab 
               (PRImA-Research-Lab) at the University of Salford. 
               This normalized and semantic description of the OCR-GT data can be found in the METS metadata file. 
               The labeling metadata is created for each available page. The following labeling metadata is available for the complete collection.</p>
   <p>Here you will find a description and explanation of the labeling metadata.</p>
   <details>
      <summary>activityDomain/computing/visual/analysisRecognition/layoutAnalysis</summary>
      <p>
         <strong>Description: </strong>In computer vision, document layout analysis is the process of identifying and categorizing the regions of interest in the scanned image of a text document. A reading system requires the segmentation of text zones from non-textual ones and the arrangement in their correct reading order.

Examples:
Page layout analysis (segmentation into regions, classification into text, graphic, table etc.)

Related:
"OCR": Often used as a synonym for layout analysis and text recognition, but strictly only the text recognition component.</p>
   </details>
   <details>
      <summary>activityDomain/computing/visual/analysisRecognition/ocr</summary>
      <p>
         <strong>Description: </strong>
      </p>
   </details>
   <details>
      <summary>activityDomain/computing/visual/analysisRecognition/text</summary>
      <p>
         <strong>Description: </strong>Translation of any kind of depicted symbols to machine readable format

Examples:
OCR
Mathematical equation recognition

Related:
Text processing (separate category)
Table recognition
Map reading</p>
   </details>
   <details>
      <summary>content-encoding/structured</summary>
      <p>
         <strong>Description: </strong>E.g. XML</p>
   </details>
   <details>
      <summary>content-type/corpus</summary>
      <p>
         <strong>Description: </strong>
Corpus: a collection of written texts, especially the entire works of a particular author or a body of writing on a particular subject.

Examples:
A text corpus,
An image database</p>
   </details>
   <details>
      <summary>contentOfInterest/visual/text</summary>
      <p>
         <strong>Description: </strong>
                        Description coming soon.
                    </p>
   </details>
   <details>
      <summary>granularity/physical/document-related/page</summary>
      <p>
         <strong>Description: </strong>
                        Description coming soon.
                    </p>
   </details>
   <details>
      <summary>granularity/physical/document-related/text-line</summary>
      <p>
         <strong>Description: </strong>
                        Description coming soon.
                    </p>
   </details>
   <details>
      <summary>platform/platform-independent</summary>
      <p>
         <strong>Description: </strong>
                        Description coming soon.
                    </p>
   </details>
</div>
<div class="metadata">
   <h2>Download</h2>
   <p>You can download the complete data here. 
                        They contain a zip file in which the components of the collection are also in zip files.
                        Metadata for the complete collection and the components are in METS format.</p>
   <ul>
      <li>
         <a href="https://github.com/bertsky/mkn-kurrent-gt/releases/tag/v0.0.5">The BagIt 'ocrd.zip' files for the current version, please download them from the latest release.: Release 5_v0.0.5</a>
      </li>
      <li>
         <a href="https://github.com/bertsky/mkn-kurrent-gt/releases">Version archive</a>
      </li>
   </ul>
</div>
<div class="metadata">
   <h2>Total view</h2>
   <table class="noStyle">
      <tr>
         <td>💡 You can show and hide individual columns of the table.<br/>Click the corresponding button.
                                <details>
               <summary>Legend</summary>
               <dl class="grid">
                  <dt>TextLine</dt>
                  <dd>TextLine</dd>
                  <dt>Page</dt>
                  <dd>Page</dd>
                  <dt>TxtRegion</dt>
                  <dd>
                     <a href="https://ocr-d.de/de/gt-guidelines/trans/lytextregion.html"
                        target="_blank">TextRegion</a>
                  </dd>
               </dl>
            </details>
         </td>
         <td>
            <div class="grid-container">
               <button onclick="document.getElementById('table_id').classList.toggle('hide1')">
                  <i>TextLine</i>
               </button>
               <button onclick="document.getElementById('table_id').classList.toggle('hide2')">
                  <i>Page</i>
               </button>
               <button onclick="document.getElementById('table_id').classList.toggle('hide3')">
                  <i>TxtRegion</i>
               </button>
            </div>
         </td>
      </tr>
   </table>
   <table id="table_id">
      <thead>
         <tr>
            <th>TextLine</th>
            <th>Page</th>
            <th>TxtRegion</th>
         </tr>
      </thead>
      <tbody>
         <tr>
            <td>19606</td>
            <td>771</td>
            <td>1220</td>
         </tr>
      </tbody>
   </table>
</div>
<div>
   <h2>Details</h2>
   <ul>
      <li>
         <a href="table">Compressed table view about regions</a>
      </li>
      <li>
         <a href="overview">Detailed table view about regions</a>
      </li>
      <li>
         <a href="overview-level">Level Matrix</a>
      </li>
   </ul>
</div>
