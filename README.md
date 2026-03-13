# SOAR-EDR-lab

[Project Workflow.drawio](https://github.com/user-attachments/files/25979024/Project.Workflow.drawio)
<mxfile host="Electron" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) draw.io/29.0.3 Chrome/140.0.7339.249 Electron/38.7.0 Safari/537.36" version="29.0.3">
  <diagram name="Page-1" id="sWoye8-xiuWYFmfbqXQ6">
    <mxGraphModel dx="438" dy="618" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="850" pageHeight="1100" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="Z2WR4E0ynXIcxkgz074u-1" value="SOAR EDR&lt;div&gt;Playbook&lt;/div&gt;" style="whiteSpace=wrap;html=1;aspect=fixed;" vertex="1" parent="1">
          <mxGeometry x="385" y="70" width="80" height="80" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-2" value="Email" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="550" y="380" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-6" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="Z2WR4E0ynXIcxkgz074u-3" target="Z2WR4E0ynXIcxkgz074u-5">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-7" value="Detection(Alert)" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];" vertex="1" connectable="0" parent="Z2WR4E0ynXIcxkgz074u-6">
          <mxGeometry x="-0.1564" y="-1" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-3" value="LimaCharlie" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="190" y="210" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-4" value="Slack" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="300" y="380" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-10" style="rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="Z2WR4E0ynXIcxkgz074u-5" target="Z2WR4E0ynXIcxkgz074u-2">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-13" value="Send Message With details" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];" vertex="1" connectable="0" parent="Z2WR4E0ynXIcxkgz074u-10">
          <mxGeometry x="0.0979" y="2" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-11" style="rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="Z2WR4E0ynXIcxkgz074u-5" target="Z2WR4E0ynXIcxkgz074u-4">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-12" value="Send Message With details" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];" vertex="1" connectable="0" parent="Z2WR4E0ynXIcxkgz074u-11">
          <mxGeometry x="0.0378" y="-3" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-16" style="rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="Z2WR4E0ynXIcxkgz074u-5" target="Z2WR4E0ynXIcxkgz074u-15">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-17" value="Isolate the machine&lt;div&gt;or not&lt;/div&gt;" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];" vertex="1" connectable="0" parent="Z2WR4E0ynXIcxkgz074u-16">
          <mxGeometry x="0.0215" y="-2" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-5" value="Tines" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="420" y="210" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-14" value="Message include:&lt;div&gt;- Time&lt;/div&gt;&lt;div&gt;- Computer Name&lt;/div&gt;&lt;div&gt;- Source IP&lt;/div&gt;&lt;div&gt;- Process&lt;/div&gt;&lt;div&gt;- Command Line&lt;/div&gt;&lt;div&gt;- File Path&lt;/div&gt;&lt;div&gt;- Sensor ID&lt;/div&gt;" style="text;html=1;whiteSpace=wrap;align=left;verticalAlign=middle;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="620" y="110" width="110" height="210" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-20" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="Z2WR4E0ynXIcxkgz074u-15" target="Z2WR4E0ynXIcxkgz074u-19">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-21" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="Z2WR4E0ynXIcxkgz074u-15" target="Z2WR4E0ynXIcxkgz074u-18">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-15" value="User Prompt" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="425" y="490" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-25" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="Z2WR4E0ynXIcxkgz074u-18" target="Z2WR4E0ynXIcxkgz074u-24">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-18" value="Yes" style="rhombus;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="310" y="600" width="80" height="80" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-33" style="rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="Z2WR4E0ynXIcxkgz074u-19" target="Z2WR4E0ynXIcxkgz074u-28">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-35" value="Message:&lt;div&gt;The machine is still active,&lt;/div&gt;&lt;div&gt;Investigate if needed&lt;/div&gt;" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];" vertex="1" connectable="0" parent="Z2WR4E0ynXIcxkgz074u-33">
          <mxGeometry x="-0.4213" y="1" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-19" value="No" style="rhombus;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="570" y="610" width="80" height="80" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-23" value="" style="image;points=[];aspect=fixed;html=1;align=center;shadow=0;dashed=0;image=img/lib/allied_telesis/computer_and_terminals/Personal_Computer_Wireless.svg;" vertex="1" parent="1">
          <mxGeometry x="120" y="735.8" width="63" height="64.2" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-32" style="rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="Z2WR4E0ynXIcxkgz074u-24" target="Z2WR4E0ynXIcxkgz074u-28">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-34" value="Message:&lt;div&gt;The Machine has been isolated&lt;/div&gt;" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];" vertex="1" connectable="0" parent="Z2WR4E0ynXIcxkgz074u-32">
          <mxGeometry x="-0.2457" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-24" value="LimaCharlie" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="290" y="740" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-28" value="Slack" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="550" y="840" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-30" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.93;entryY=0.526;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="1" source="Z2WR4E0ynXIcxkgz074u-24" target="Z2WR4E0ynXIcxkgz074u-23">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="Z2WR4E0ynXIcxkgz074u-31" value="Isolates&lt;div&gt;machine&lt;/div&gt;" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];" vertex="1" connectable="0" parent="Z2WR4E0ynXIcxkgz074u-30">
          <mxGeometry x="-0.0359" y="-1" relative="1" as="geometry">
            <mxPoint x="1" as="offset" />
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
